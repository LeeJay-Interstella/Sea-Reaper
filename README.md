# ⚓ Sea Reaper

**Sea Reaper** — a pirate ship management game where your vessel is the hero. Upgrade it, dispatch it on voyages, and await its return. Battles play out in a classic turn-based combat screen. The world shifts with your real local time — new routes at dawn, a black market at night, and random events after dark.

---

## 🎮 Play

Open `index.html` in any modern browser — no install, no dependencies.

Or visit the live demo: **[your-github-username.github.io/sea-reaper](https://your-github-username.github.io/sea-reaper)**

---

## 🚢 Features

- **Ship as sole protagonist** — no crew, no cast. Upgrade your vessel across four stat paths (Hull, Cannons, Speed, Cargo), each one visibly transforming the ship sprite
- **Voyage loop** — dispatch the ship, await its return, resolve the outcome. Safe return, battle, or rare catch
- **Turn-based battles** — static combat screen with HP bars, four actions (Broadside, Board, Patch, Flee), and three enemy types
- **Day / Night system** — geolocation-aware phases (Dawn, Day, Dusk, Night) with exclusive voyages, a night black market, and random events after dark
- **Dock Market** — sell your voyage fish haul, rare sea catches (octopus, shark, giant squid...), buy rum and repairs
- **Captain's Log** — colour-coded record of every voyage, battle, and trade
- **Mobile-first** — responsive layout, fixed bottom nav bar, works on any device

---

## 🌙 Day / Night Phases

| Phase | Hours | Exclusive Content |
|-------|-------|-------------------|
| ☀️ Day | 07:00 – 18:00 | Coastal Patrol, Merchant Lanes, Naval Blockade |
| 🌅 Dawn | 05:00 – 07:00 | Early Morning Raid |
| 🌇 Dusk | 18:00 – 21:00 | Last Light Plunder |
| 🌙 Night | 21:00 – 05:00 | Smuggler's Run, Ghost Ship Waters, Black Market, Random Events |

---

## ⚒️ Upgrades

| Upgrade | Effect | Max Level |
|---------|--------|-----------|
| Iron Cannons | +12 Cannon per level | 4 |
| Reinforced Hull | +15 Hull per level | 4 |
| Silk Sails | +14 Speed per level | 4 |
| Cargo Holds | +20 Cargo per level | 4 |

Each upgrade visually changes the ship sprite.

---

## 📁 Structure

```
sea-reaper/
├── index.html      # Complete game — single self-contained file
└── README.md
```

---

## 🗺️ Roadmap

- [ ] Real-world voyage timers + push notifications
- [ ] Persistent save state / cloud sync
- [ ] Ship name & skin customisation
- [ ] Ghost ship night enemy type
- [ ] Day/night ambient soundscapes
- [ ] Seasonal events (storms, Halloween, winter)
- [ ] Leaderboards & reputation rankings

---

## 📄 Licence

MIT — free to use, fork, and build upon.

---

*Built as an HTML5 MVP concept. Single file, zero dependencies.*
