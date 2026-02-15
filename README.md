# SIREN V3 — Interactive Demo

**Signature-Based Intelligent Resource and Energy Network**
*Predictive Maintenance through Energy Signatures*

> Patent Pending · USPTO Application 63/983,192

---

## What is SIREN?

SIREN uses **electrical current as a universal sensor** to predict equipment failures before they happen. No vibration sensors, no temperature probes, no retrofitting — just a CT clamp on the power line.

Every electromechanical component has a unique energy signature. When that signature drifts, SIREN knows something is changing — weeks or months before traditional monitoring systems detect it.

## Live Demo

**→ [siren-v3-demo.onrender.com](https://siren-v3-demo.onrender.com)**

## Features Demonstrated

### 5 Industry Domains
- **🏭 Industrial Manufacturing** — CNC machining centers (DMG MORI DMU 50 / FANUC ROBODRILL)
- **🤖 Humanoid Robotics** — Next-gen robots (Figure 02 / Tesla Optimus Gen 2)
- **📦 Intralogistics** — Autonomous mobile robots (KUKA KMP 1500P / Jungheinrich arculee)
- **💨 Wind Energy** — Offshore turbines (Vestas V150-6.0MW / Siemens Gamesa SG 6.6-170)
- **🏥 Healthcare** — MRI systems (Siemens MAGNETOM Vida 3T / GE SIGNA Premier 3T)

### OEM Toggle
Each domain features two competing OEMs with real product specifications, demonstrating SIREN's configurability across different equipment manufacturers.

### 5 Interactive Tabs
1. **⚡ Live Monitor** — Real-time waveform visualization, component status, drift detection
2. **🧠 Intelligenz** — Analysis depth levels, real-world scenarios, differential diagnosis
3. **🔧 Frühwarnung** — Early warning system, SIREN vs. traditional sensors comparison
4. **💼 Business Case** — ROI calculator for end customers and OEM integration perspective
5. **🌐 Fleet Dashboard** — Fleet-wide monitoring, service route optimization, ticket management

### Patent-Covered Innovations Shown
- **Environmental Context Integration** — Weather forecast affects baseline adjustment and risk assessment
- **Power Quality Monitoring** — Grid frequency, THD, voltage stability as additional context layer
- **Differential Diagnosis** — Automatic triage: component vs. system vs. fleet-wide issue
- **Integrity Chain** — SHA-256 hash chain for tamper-proof audit trail (animated, live)
- **Environment History** — Animated 12-month learning timeline showing pattern recognition over time
- **Configurable Architecture** — One core engine, multiple domains via configuration profiles

## Technology

Single-file HTML application. No build step, no dependencies, no backend required.

- Vanilla JavaScript
- CSS Grid/Flexbox
- HTML5 Canvas (waveform animation)
- Leaflet.js (fleet maps via CDN)
- Google Fonts (Syne, JetBrains Mono)

## Deployment

### Static Hosting (Render, Netlify, Vercel, GitHub Pages)
Just serve `index.html`. That's it.

### Local
```bash
# Clone and open
git clone https://github.com/xloop3/siren-v3-demo.git
cd siren-v3-demo
open index.html
```

## About

**X-Loop³ Labs** — AI Infrastructure & Governance, Gossau SG, Switzerland

SIREN is a patent-pending technology for predictive maintenance of autonomous electromechanical systems. This repository contains a demonstration visualization only — not the core engine, algorithms, or production code.

## License

© 2025–2026 X-Loop³ Labs. All rights reserved.

This demo is provided for evaluation and demonstration purposes. The underlying SIREN technology is protected under USPTO Patent Application 63/983,192. Unauthorized commercial use of the demonstrated concepts is prohibited.

---

*Built with precision in Switzerland 🇨🇭*
