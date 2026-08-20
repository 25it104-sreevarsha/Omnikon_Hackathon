# GrainGuard AI

**Team HarvestGuard** — Omnikon National Hackathon 2026
**Problem Statement:** Omni_AgriTech_8 — Reducing Grain Spoilage in Rural Storage

## Overview

GrainGuard AI is a smart spoilage-risk advisor for rural grain storage. Workers photograph the grain heap through the mobile app; an AI vision model checks for early mold, discoloration, or pest damage, while a risk engine combines this with grain-science moisture/temperature thresholds and hyperlocal weather forecasts to compute a live Spoilage Risk Score (Low / Medium / High). The app returns one clear, voice-guided instruction in the worker's local language — no hardware required for the MVP, with an optional ESP32 + DHT22 sensor tier for warehouses that want continuous live monitoring.

## Key Features

- Photo-based Spoilage Risk Score — zero hardware needed
- AI vision model for early mold/pest detection
- Weather-aware prediction using Open-Meteo forecasts
- Voice + local-language alerts for low-literacy users
- Optional live sensor tier (ESP32 + DHT22)
- Manager dashboard with risk history across storage units

## Tech Stack

- **Frontend:** React Native / Flutter
- **Backend:** Node.js + Express
- **Database:** Firebase / MongoDB
- **AI/ML:** MobileNet image model + rule-based risk engine
- **Weather API:** Open-Meteo (free tier)
- **Optional Hardware:** ESP32 + DHT22
- **Notifications:** Firebase Cloud Messaging + local-language TTS

## Getting Started

> Setup instructions will be added here once the initial project scaffold is committed.

```bash
# Clone the repo
git clone <repo-url>
cd grainguard-ai

# Install dependencies
npm install

# Run locally
npm run dev
```

## Contributors

| Name | GitHub Username | Role |
|------|------------------|------|
| Sree Varsha M | @TBD | Team Lead — Backend & AI Integration |
| Suvetha S | @TBD | Frontend & UI/UX |

> Only registered participants of Team HarvestGuard contribute to this repository. All contributions reflect the work of the listed team members; AI coding tools are used as assistive tools per hackathon rules.

## License

TBD
