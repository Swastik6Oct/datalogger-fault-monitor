# 🚆 Railway Datalogger Fault Monitoring System

An n8n workflow for monitoring Railway datalogger SMS faults and displaying live status on a dashboard.

## Features

- 📩 Receives SMS from Telerivet
- ⚙️ Parses fault and restoration messages
- 🗄️ Stores incidents in PostgreSQL
- ⏱️ Calculates downtime automatically
- 📊 Live HTML dashboard
- 🔄 Designed for Railway Signal & Telecommunication maintenance

## Workflow

SMS
↓
Telerivet
↓
n8n
↓
PostgreSQL
↓
Dashboard

## Tech Stack

- n8n
- PostgreSQL
- Telerivet
- HTML
- JavaScript

## Repository Contents

- `SMS Dashboard.json` — Exported n8n workflow

## License

MIT
