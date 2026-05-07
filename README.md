#  SMARTRIDE SALONE
### Climate-Resilient Mobility Intelligence Platform · Sierra Leone

[![Status](https://img.shields.io/badge/status-prototype-orange)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()
[![SDG](https://img.shields.io/badge/SDG-3%20%7C%2011%20%7C%2013-blue)]()

> Real-time mobility intelligence to improve climate resilience and healthcare access for vulnerable communities in Sierra Leone.

---

##  The Problem

Sierra Leone faces increasing climate-related disruptions — flooding and heavy rainfall that severely impact transportation and delay access to healthcare. Vulnerable communities, especially children, face life-threatening delays when roads are blocked and there is no real-time information to guide safer movement.

## 💡 The Solution

SMARTRIDE SALONE is a GPS-based mobility intelligence platform that:

- **Maps route conditions in real time** — safe, caution, and blocked routes
- **Overlays flood risk zones** on an interactive map of Freetown
- **Enables community reporting** — anyone can report blocked roads
- **Tracks healthcare facility accessibility** during climate disruptions
- **Logs GPS route data** to build a growing mobility dataset

##  Live Prototype

**[→ View Live Demo](https://smartride-salone-climate-health-mobility.onrender.com)**

##  Technologies

| Layer | Technology |
|---|---|
| Map Engine | Leaflet.js + OpenStreetMap |
| GPS Tracking | Browser Geolocation API |
| Flood Data | GloFAS (planned) · Manual overlay (prototype) |
| Hosting | Render (static site) |
| Future: AI/ML | Route disruption prediction models |
| Future: Backend | FastAPI + PostGIS |
| Future: Mobile | React Native (Android-first) |

##  Repository Structure

```
smartride-salone/
├── index.html          # Full prototype (single-file)
├── README.md           # This file
└── render.yaml         # Render deployment config
```

##  Running Locally

No build step required. Just open `index.html` in any browser:

```bash
git clone https://github.com/YOUR_USERNAME/smartride-salone.git
cd smartride-salone
open index.html
```

##  Deploying to Render

1. Push this repo to GitHub
2. Go to [render.com](https://render.com) → New → Static Site
3. Connect your GitHub repo
4. Set **Publish directory** to `.` (root)
5. Click **Deploy**

Or use the included `render.yaml` for automatic configuration.

##  Prototype Features (v0.1)

- [x] Interactive map centered on Freetown, Sierra Leone
- [x] Color-coded route overlays (safe / caution / blocked)
- [x] Flood risk zone visualization
- [x] Healthcare facility markers with access status
- [x] Community road condition reporting form
- [x] GPS route tracking (with demo simulation fallback)
- [x] Community report pins on map
- [x] Satellite / street tile toggle
- [x] Analytics dashboard (mobility data overview)
- [x] Mobile-responsive layout

##  12-Month Roadmap

- [ ] Mobile app (Android-first via React Native)
- [ ] Real-time flood data integration (GloFAS API)
- [ ] AI-driven disruption prediction
- [ ] Offline-capable route data
- [ ] Open-source Digital Public Good release
- [ ] Pilot testing in flood-prone communities
- [ ] Partnerships with health and transport stakeholders

##  Team

A multidisciplinary team of 5 working across software development, finance, communications, and community engagement — with direct field experience supporting vulnerable children in Sierra Leone.

##  Alignment

- **Digital Public Goods** — Open-source, designed for low-resource settings
- **SDG 3** — Good Health & Well-Being
- **SDG 11** — Sustainable Cities & Communities
- **SDG 13** — Climate Action

##  License

MIT License — open for adaptation and reuse.

----

*SMARTRIDE SALONE · Prototype v0.1 · 2025* 
