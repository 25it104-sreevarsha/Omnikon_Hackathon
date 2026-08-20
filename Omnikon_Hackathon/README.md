# GrainGuard AI 🌾
### Predictive Spoilage Risk Advisor — Team HarvestGuard

**Hackathon:** OMNIKON National Hackathon 2026
**Theme:** Software / AgriTech
**Problem Statement:** Reducing Grain Spoilage in Rural Storage

---

## 📌 Problem

Poor storage conditions in rural warehouses cause **10–20% of the global grain harvest** to be lost every year. Most tech fixes assume sensor budgets that rural storage units simply don't have.

## 💡 Our Solution

**GrainGuard AI** is a zero-hardware MVP that turns a simple photo of a grain heap into a live **Spoilage Risk Score**, combining AI vision, grain-science thresholds, and hyperlocal weather forecasts — delivered as one clear, voice-guided instruction in the worker's own language.

### Key Features
- 📸 **Photo Risk Scan** — instant risk score, no setup needed
- 🤖 **Early Defect Detection** — AI vision flags mold, discoloration & pest damage
- 🌦️ **Weather-Aware Forecast** — predicts risk before it spikes
- 🔊 **Voice + Local Language** — accessible for low-literacy workers
- 🔌 **Optional Sensor Mode** — ESP32 + DHT22 for live continuous monitoring
- 📊 **Manager Dashboard** — track risk across multiple storage units

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Frontend | React Native / Flutter |
| Backend | Node.js + Express |
| AI/ML | MobileNet image model + rule-based Spoilage Risk Engine |
| Data & APIs | Firebase / MongoDB + Open-Meteo Weather API |
| Hardware (optional) | ESP32 + DHT22 |

## 📁 Repository Structure

```
Omnikon_Hackathon/
├── frontend/       # Mobile app (worker-facing UI)
├── backend/        # API, auth, orchestration
├── ai-model/        # Vision model + risk engine logic
├── assets/         # Diagrams, mockups, images
├── docs/           # Problem statement, submission deck, notes
└── README.md
```

## 🚀 Project Status

🟢 **Phase 1 complete** — Idea submitted and approved
🟡 **Phase 2 in progress** — Repository initialized, development starting

## 👥 Team & Contributors

| Name | Role | GitHub Username |
|---|---|---|
| Sree Varsha M | Team Lead / Full-stack & AI Integration | [@25it104-sreevarsha](https://github.com/25it104-sreevarsha) |
| Suvetha S | Frontend & UX / Documentation | *(add GitHub username)* |

> All team members are registered OMNIKON 2026 participants and have contributed equally to this project.

## 🔗 Links

- Repository: https://github.com/25it104-sreevarsha/Omnikon_Hackathon
- Phase 1 Submission: see `docs/` folder

---
*One Mission. Build the Impossible.*
