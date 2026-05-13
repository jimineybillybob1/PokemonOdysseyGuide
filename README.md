# Pokémon Odyssey — Companion Guide

A modern, fully interactive companion guide for **Pokémon Odyssey**, the Pokémon ROM Hack.

Designed as a sleek all-in-one reference tool built as a lightweight single-page HTML app — no installation required, works directly in the browser, and can be installed as a Progressive Web App (PWA).

---

## ✨ Features

| Section | Description |
|---|---|
| 📖 **Pokédex** | Searchable Pokédex with type filtering, evolution info, abilities, base stats, and full learnsets |
| 🌿 **Encounters** | Area-by-area wild encounter tables with rates, levels, and per-Pokémon catch tracking |
| ⭐ **Etrian Variants** | Highlights all Etrian Variant Pokémon and their evolution paths |
| ⚡ **Events & Gifts** | Event encounters, trades, and sidequest rewards with obtained tracking |
| 💀 **F.O.E. Encounters** | Boss-style overworld encounters organised by region |
| ⚓ **Naval Exploration** | Naval encounter tables and expedition groups by Strata |
| 💿 **TM Locations** | Full TM list with move effects and where to obtain each one |
| 🎓 **Move Tutors** | Move tutor locations and full move reference |
| 📜 **Side Quests** | Quest descriptions, locations, and reward tracking |
| 🗺️ **Sea Map** | Integrated Odyssey sea map reference |
| 💡 **New Moves & Abilities** | Odyssey-exclusive moves, Aether-type moves, buffed moves, and new abilities |

### Additional features

- 💾 Catch and quest progress auto-saves in-browser via LocalStorage — persists between sessions
- 📱 Fully responsive — works on desktop and mobile
- ⚡ PWA-ready — installable as a home screen app on Android and iOS
- 🔍 Search and filter across every section

---

## 🚀 Getting Started

### Option 1 — Run locally

1. Clone or download this repository
2. Open `index.html` in any modern browser

That's it — no build step, no dependencies.

### Option 2 — Host on GitHub Pages

1. Push the repo to GitHub (you're already here)
2. Go to **Settings → Pages**
3. Set Source to **Deploy from branch**, branch to `main`, folder to `/ (root)`
4. Save — your guide will be live at `https://<your-username>.github.io/PokemonOdysseyGuide/`

---

## 📂 File Structure

```
PokemonOdysseyGuide/
├── index.html          # The entire app — HTML, CSS, and JS all in one file
├── manifest.json       # PWA manifest for install prompts and app metadata
├── icons/              # PWA icons (72×72 → 512×512 + maskable)
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-180.png
│   ├── icon-192.png
│   ├── icon-512.png
│   └── maskable-icon-512.png
└── README.md
```

---

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage API

No frameworks. No build tools. No dependencies.

---

## 📌 Notes

- Odyssey learnsets may differ from standard Pokémon games — data is sourced from community guide sheets and in-game information
- Etrian Variant sprites are custom; refer to the [official Etrian Variants sheet](https://docs.google.com/spreadsheets/d/1Es1clPMUhEEqZRHW0tgAmvxqSzVXiXmD/edit?gid=1620070709) for visuals
- Progress is stored locally in your browser and is **not** cloud synced
- Pokémon sprites are loaded from the [PokeAPI sprites repository](https://github.com/PokeAPI/sprites)

---

## 🔗 Useful Resources

- [Official F.O.E. & Naval Guide Sheet](https://docs.google.com/spreadsheets/d/1-duiiF5TXQtI3E9BdyXEViYYYVel_sUstNk1lZCqHsE/edit?gid=25816556)
- [Official Etrian Variants Sheet](https://docs.google.com/spreadsheets/d/1Es1clPMUhEEqZRHW0tgAmvxqSzVXiXmD/edit?gid=1620070709)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

---

## ⚠️ Disclaimer

Pokémon is owned by Nintendo, Game Freak, and The Pokémon Company. This project is a fan-made companion guide created for educational and community purposes only. No copyright infringement is intended.

---

## ❤️ Credits

Created for fans of Pokémon Odyssey and the wider Pokémon ROM Hack community. Massive respect to the developers and community contributors keeping the ROM hack scene alive.
