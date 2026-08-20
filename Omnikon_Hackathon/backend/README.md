# Backend

Node.js + Express API — handles auth, photo upload, orchestration between AI model and weather API.

**Status:** Setup pending — Phase 2

## Planned Endpoints
- `POST /api/scan` — submit photo + basic conditions, get Spoilage Risk Score
- `GET /api/units/:id/history` — risk history for a storage unit
- `GET /api/weather/:location` — hyperlocal forecast lookup
