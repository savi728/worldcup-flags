# 🏆 Know Your Flags · 认识国旗

**An interactive flag-learning app for the 2026 FIFA World Cup.**  
48 teams. Bilingual. Dark mode. Quiz included.

🌐 **Live site → [worldcup-flags.vercel.app](https://worldcup-flags.vercel.app)**

---

## What it does

The 2026 World Cup is the biggest ever — 48 teams, 6 continents, 12 groups. If you've ever watched a match and thought *"wait, which country is that flag?"* — this is for you.

| Tab | What you get |
|-----|-------------|
| 🏴 **Flags** | All 48 teams in a searchable, filterable grid. Click any card for the flag's full story. |
| ⚽ **Groups** | Group stage layout (A–L) with every team. Click a team to see details. |
| 🎯 **Quiz** | Show a flag, pick the right country from 4 options. Tracks score, streak, and accuracy. |

Each country card shows:
- The national flag
- English name + Chinese name (中英文对照)
- Confederation badge (UEFA / CONMEBOL / CAF / AFC / CONCACAF / OFC)

Each detail modal shows:
- Capital city
- World Cup group
- Historical best result
- **Flag meaning** — what the colors, symbols, and shapes actually represent, in both English and Chinese

---

## Features

- **Bilingual** — English first, Chinese second throughout; flag meanings written in both languages
- **Dark / Light mode** — toggle with ☀️/🌙 in the header; preference saved in `localStorage`
- **Search** — filter by country name in English or Chinese
- **Continent filter** — narrow down to any of the 6 confederations
- **Quiz** — streak counter, progress dots, accuracy percentage
- **Zero dependencies** — pure HTML + CSS + vanilla JS, single file, no build step

---

## Tech

```
index.html        — the entire app (HTML + CSS + JS, ~720 lines)
```

No framework. No build tool. No npm. Just one file that opens in a browser.

Deployed on **Vercel** via GitHub — any `git push` to `main` auto-deploys.

---

## Development

```bash
# Clone and open locally — no install needed
git clone https://github.com/savi728/worldcup-flags.git
cd worldcup-flags
open index.html
```

To deploy a change:

```bash
git add index.html
git commit -m "your message"
git push     # Vercel picks it up automatically
```

---

## Data notes

- All 48 World Cup 2026 qualified teams are included (based on confirmed qualifications as of mid-2025)
- Group assignments (A–L) are **illustrative** — the official draw took place in December 2025; check [fifa.com](https://fifa.com) for the authoritative groupings
- Flag meanings are written to be accurate and educational, not exhaustive

---

## Screenshots

| Dark mode | Light mode |
|-----------|------------|
| ![dark](https://worldcup-flags.vercel.app/og-dark.png) | ![light](https://worldcup-flags.vercel.app/og-light.png) |

*(Open the live site for the full experience — flag emojis render best in a browser)*

---

<p align="center">
  Made during the 2026 FIFA World Cup &nbsp;·&nbsp; 世界杯加油 ⚽
</p>
