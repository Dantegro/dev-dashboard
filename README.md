# 🧠 Dev Dashboard

A self-hosted developer dashboard powered by [Homepage](https://gethomepage.dev) to monitor and launch all local development tools.

---

## 🧰 Features

- 📊 CPU / RAM / Disk usage widgets
- 🛠 Quick links to local dev services:
  - Next.js (Frontend)
  - NestJS (Backend API)
  - Prisma Studio
  - Supabase Studio
  - Swagger Docs
  - pgAdmin
- 📚 Bookmarks to docs (Next.js, NestJS, Prisma, Supabase)
- 📂 Fully YAML-configurable
- 🐳 Dockerized — easy to launch and manage

---

## 🚀 Getting Started

### 1. Clone this repo

```bash
git clone https://github.com/Dantegro/dev-dashboard.git
cd dev-dashboard
2. Run with Docker
bash
Copy
Edit
docker compose up -d
Then open: http://localhost:3001

🧾 Project Structure
bash
Copy
Edit
.
├── config/
│   ├── config.yaml        # Global dashboard config
│   ├── services.yaml      # Services (Next.js, NestJS, etc.)
│   ├── bookmarks.yaml     # Documentation + GitHub links
│   └── widgets.yaml       # CPU / RAM / Search bar widgets
└── docker-compose.yml     # Launches Homepage container
🧠 Credits
This dashboard is powered by Homepage, a modern, customizable dashboard for developers and self-hosters.

sql
Copy
Edit

✅ Once saved, commit and push it:

```bash
git add README.md
git commit -m "Add README.md for dev dashboard"
git push
