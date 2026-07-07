# 🏆 Football API — Open Data for World Cup & AFCON

A **free, open-source dataset** for major international football competitions — including the FIFA World Cup, Africa Cup of Nations (AFCON), and other global tournaments.

All data is provided in **JSON** and **CSV** formats, making it easy for developers, analysts, and content creators to build apps, dashboards, and football content **without restrictions**.

---

## 🎯 Project Goal

The goal of this project is simple:

> Give developers **100% control** over their football API — with **no rate limits**, **no daily quotas**, **no API keys**, and **no usage restrictions**.

By forking this repository, you can host your own football API anywhere (GitHub Pages, Cloudflare, Vercel, Netlify, or your own server) and maintain complete ownership of the data.

---

## 📂 What’s Inside

All datasets are provided in both **JSON** and **CSV** formats:

- **Competitions** — World Cup, AFCON, qualifiers, and more.
- **Teams** — National teams, federations, confederations.
- **Squads** — Player lists, positions, ages, clubs.
- **Matches** — Fixtures, results, dates, stadiums.
- **Lineups** — Starting XI, substitutes, formations.
- **Statistics** — Goals, cards, standings, group tables.
- **Historical Data** — Past tournaments, legendary teams.

Every file is structured for easy parsing and integration into apps, websites, or analytics tools.

---

## 🚀 Why This Repository Exists

Most football APIs have:

- ❌ Rate limits
- ❌ Daily quotas
- ❌ API keys
- ❌ Paid tiers
- ❌ Restricted endpoints

**This project removes all of that.**

You get:

- ✔ Unlimited requests
- ✔ Full access to raw data
- ✔ Ability to host your own API
- ✔ Freedom to modify, expand, or translate the dataset
- ✔ Zero dependency on external services

**This is your football API, not someone else’s.**

---

## 🔧 How to Use

You can use the data in multiple ways:

1. **Fork the repository**  
   Create your own version and customize the data.

2. **Host it as a static API**  
   Serve JSON files directly from:
   - GitHub Pages
   - Cloudflare Pages
   - Vercel
   - Netlify
   - Your own server

3. **Import the data into your app**  
   Works great with:
   - JavaScript / TypeScript
   - Python
   - PHP
   - Go
   - Rust
   - Mobile apps (React Native, Flutter, etc.)
   - Dashboards & Data analysis notebooks

4. **Build content**  
   Perfect for bloggers, YouTubers, sports analysts, and creators who want reliable football data.

---

## 📦 Example JSON Structure

```json
{
  "match_id": 101,
  "competition": "World Cup",
  "stage": "Group A",
  "date": "2022-11-21",
  "teams": {
    "home": "Qatar",
    "away": "Ecuador"
  },
  "score": {
    "home": 0,
    "away": 2
  },
  "stadium": "Al Bayt Stadium",
  "referee": "Daniel Siebert"
}


