# 🏔️ St. George Marathon 2026 — Training Plan

**Hansons Beginner Method · 18 Weeks · Race Day: October 3, 2026**  
**Goal: 3:50–4:10 · 9:09/mi marathon pace**

A fully offline-capable Progressive Web App (PWA) containing every single training day from June 1 through October 3, 2026 — with daily distance, pace, workout breakdown, coaching tips, and motivation.

---

## 📱 Install on iPhone (Add to Home Screen)

1. Open your deployed URL in **Safari** (not Chrome)
2. Tap the **Share button** (box with arrow pointing up)
3. Scroll down → tap **"Add to Home Screen"**
4. Name it `St George 26.2` → tap **Add**

It now lives on your home screen like a native app and **works offline**.

---

## 🚀 Deploy Options

### Option A — Netlify (Recommended, 60 seconds)

1. Push this repo to GitHub
2. Go to [netlify.com](https://netlify.com) → **"Add new site"** → **"Import an existing project"**
3. Connect GitHub → select this repo
4. Build settings: leave everything blank (no build command needed)
5. Click **Deploy** — done

Or use **Netlify Drop** (no account needed):
- Go to [netlify.com/drop](https://app.netlify.com/drop)
- Drag and drop the `index.html` file

---

### Option B — GitHub Pages

1. Push this repo to GitHub
2. Go to repo **Settings** → **Pages**
3. Under "Source" select **Deploy from a branch**
4. Select branch: `main` · folder: `/ (root)`
5. Click **Save** — live in ~60 seconds at `https://yourusername.github.io/st-george-marathon`

---

## 📁 Repo Structure

```
st-george-marathon/
├── index.html        # The entire app — self-contained, no dependencies
└── README.md         # This file
```

No build step. No npm install. No dependencies. One file does everything.

---

## ✅ Features

- **Auto-jumps to current week** based on today's date
- **Live race countdown** (days until Oct 3) in every week header
- **Tap any day** to expand full workout breakdown, paces, coaching tip & motivation
- **Phase navigation** — jump between BASE / SPEED / STRENGTH / TAPER / RACE WEEK
- **Works fully offline** once loaded
- **iPhone home screen ready** (PWA — full screen, no browser chrome)

---

## 🏃 The Plan at a Glance

| Phase | Weeks | Focus |
|-------|-------|-------|
| BASE | 1–5 | Easy miles only · build to 29 mi/wk |
| SPEED | 6–10 | 400m–1200m repeats @ 5K pace · tempo begins |
| STRENGTH | 11–16 | Mile repeats @ MP-10s · tempo to 10mi · long run to 16mi |
| TAPER | 17 | Volume drops 30% · final SOS workouts |
| RACE WEEK | 18 | Easy shakeouts · expo Friday · race Saturday |

**Peak week:** 57 miles (Week 16)  
**Longest long run:** 16 miles (Weeks 14–16)  
**Final SOS workout:** 11 days before race

---

*Built with the Hansons Marathon Method by Luke Humphrey.*
