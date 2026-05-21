<div align="center">

# 🛡️ Browser Sentinel

### See what's happening inside your browser — in real time.

One playful dashboard for the four things your browser hides from you:
**resource hogs · trackers · traffic · network.** Open it, fix it in one click.

[![Status](https://img.shields.io/badge/status-in%20development-10B981)](#)
[![Platform](https://img.shields.io/badge/platform-Chrome%20MV3-1E293B)](#)
[![License](https://img.shields.io/badge/license-MIT-64748B)](#)

🌐 **[Landing page](https://jiakunhuang.github.io/browser-sentinel/)** &nbsp;·&nbsp; ⭐ Coming soon to the Chrome Web Store

</div>

---

## What is this?

Chrome's built-in task manager is ugly and engineer-only. uBlock blocks trackers
silently — you never get to *see* it work. Browser Sentinel turns all of that into
a dashboard you actually want to open, with a health score, gamified cards, and a
one-click fix for everything it finds.

> **Note:** This project is in active development. The extension is not yet published.
> Star the repo to follow the build.

## ✨ Core modules

| Module | What it does |
|---|---|
| ⚡ **Resource Assassins** | Live CPU / memory / battery per tab. Heavy tabs become "wanted cards" — close them in one click. |
| 🕵 **Tracker Radar** | Detects who's tracking you, the company behind each tracker, and lets you block them instantly. |
| 📊 **Traffic Monitor** | A leaderboard of which sites eat your bandwidth, with alerts and a monthly recap. |
| 🌐 **Network Pulse** | Passive page-load analysis — a "detective report" of what slowed you down. |
| 🎯 **Health Score** | Combines all four into a single 0–100 score with a one-line AI quip. |

## 🧰 Tech stack

- **Extension:** Manifest V3 · TypeScript · React · Tailwind CSS · Recharts · IndexedDB
- **Backend:** Go · PostgreSQL · Redis (license verification + AI quips)
- **Payments:** one-time Pro unlock ($14.9), no subscription

## 💸 Pricing

- **Free** — all four live modules, manual actions, 7-day history (ad-supported)
- **Pro** — $14.9 once, lifetime: no ads, auto mode, unlimited history, PDF reports, custom weights

## 🗺️ Roadmap

- [x] Product spec & design
- [ ] Extension scaffold (Vite + React + TS)
- [ ] Module 1–4 implementation
- [ ] Health score + gamification layer
- [ ] Go backend + payments
- [ ] Chrome Web Store submission

## 📬 Stay in the loop

Want to know when it ships? Email **jiakunhuang@hotmail.com** or watch this repo.

---

<sub>Independent project · not affiliated with, endorsed by, or sponsored by Google LLC.
"Chrome" and "Chrome Web Store" are trademarks of Google LLC.</sub>
