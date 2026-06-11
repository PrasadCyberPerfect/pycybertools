# 🔐 PyCyberTools v2.0 — Full Stack Deployment Guide

## Structure
```
prasad/PyCyberTools/
├── frontend/          ← Deploy on Vercel.com (free)
│   ├── index.html
│   └── vercel.json
├── backend/           ← Deploy on Render.com (free)
│   ├── app.py
│   ├── tools/engine.py
│   ├── requirements.txt
│   ├── Procfile
│   └── render.yaml
└── README.md
```

## Quick Deployment (5 steps total)

### Step 1 — Deploy Backend on Render.com
1. Create GitHub repo: `pycybertools-api`
2. Upload the `backend/` folder contents
3. Go to render.com → New Web Service → Connect repo
4. Click Deploy → wait 2 minutes
5. Copy your URL: `https://pycybertools-api.onrender.com`

### Step 2 — Update API URL in Frontend
Open `frontend/index.html`, find line ~10:
```js
const API = "https://pycybertools-api.onrender.com";
```
Replace with your actual Render URL.

### Step 3 — Deploy Frontend on Vercel
1. Create GitHub repo: `pycybertools`
2. Upload the `frontend/` folder contents
3. Go to vercel.com → New Project → Import repo
4. Click Deploy → done!
5. Your live URL: `https://pycybertools.vercel.app`

## Author
PrasadCyberPerfect — https://github.com/PrasadCyberPerfect
