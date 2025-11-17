# Fullstack Docker App (minimal placeholder)

This repository contains a minimal full-stack app for the class assignment.

- `Backend/` - Node + Express API
- `Frontend/` - Minimal React frontend (served by nginx)
- `db-data/` - directory used for Postgres data volume
- `.env` - DB credentials used by `docker-compose.yml`
- `docker-compose.yml` - Compose file to run DB, backend, and frontend

How to run locally:

```powershell
Set-Location 'C:\Users\Mohammed Shammas\OneDrive\Desktop\fullstack-docker-app'
docker compose up --build
```

Visit `http://localhost:3000` to see the frontend and API response.
