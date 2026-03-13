# 🏰 Realm Siege — Strategic Tower Defense

> A fully featured, mobile-first tower defense game built in a **single HTML file** — no frameworks, no dependencies, no build step required. Now available as an Android app!

![Platform](https://img.shields.io/badge/Platform-Browser%20%7C%20Android-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-Ready-purple?style=flat-square)
![Android](https://img.shields.io/badge/Android-APK%20%7C%20AAB-brightgreen?style=flat-square)
![Built with Claude](https://img.shields.io/badge/Built%20with-Claude%20AI-orange?style=flat-square)

---

## 🎮 Play Now

🌐 **Browser:** [Play on Netlify](https://saumyajyoti0406.github.io/Realm_Seige_Tower_Defence_Game)

📱 **Android:** Download the APK from the [Releases](../../releases) section and install directly on your device

---

## 🤖 Built with Claude AI

This game was designed and built with the help of **[Claude](https://claude.ai)** by Anthropic — an AI assistant that helped:
- Architect and code the entire game engine from scratch
- Design the tower, enemy, and progression systems
- Build the sign-in and per-user save system
- Convert the game into a fully installable Android PWA
- Generate the app icon and all supporting assets

> *Proof that anyone can build and ship a real game with the right tools — no prior game dev experience needed!*

---

## 📱 Android Installation

### Option 1 — Direct APK Install
1. Download `Realm Siege.apk` from [Releases](../../releases)
2. On your Android phone, open the APK file
3. If prompted, enable **"Install from unknown sources"** in settings
4. Install and enjoy! 🎮

### Option 2 — Play in Browser (Chrome on Android)
1. Open the game link in **Chrome**
2. Tap the banner: **"Add Realm Siege to Home Screen"**
3. It installs like a real app — works offline too!

---

## ✨ Features

### 🗺️ Campaign
- **4 unique worlds** — Verdant Forest, Scorched Sands, Lava Fields, Frozen Peaks
- **8 levels per world** (32 total) including boss encounters every 4th level
- Star rating system (1–3 ⭐) based on lives remaining at victory
- **Beginner-friendly** — first 3 levels have extra gold, more lives, and fewer enemies

### 🏗️ Towers
| Tower | Unlock | Special |
|-------|--------|---------|
| 🏹 Archer | Level 1 | Balanced, rapid fire |
| 💣 Cannon | Level 2 | AoE splash damage |
| 🔮 Magic | Level 4 | Ignores enemy armor |
| ❄️ Frost | Level 6 | Slows enemies |
| ☠️ Poison | Level 8 | Damage-over-time |
| ⚡ Tesla | Level 12 | Chain lightning |

Every tower has a **3-tier upgrade tree** with branching paths at tier 3 for meaningful strategic choices.

### 🧝 Heroes
- **Lyra** 🧝 — Root & gold aura
- **Kael** 🧙 — Fireball AoE
- **Serafin** 🧊 — Blizzard aura

### ⚡ Abilities
| Ability | Effect |
|---------|--------|
| ❄️ Freeze | Freeze all enemies for 3s |
| ⚡ Storm | Chain lightning hits 10 enemies |
| ☄️ Meteor | Massive AoE explosion |
| ⏳ Time Warp | Double speed for 8s |
| 🏹 Barrage | Triple archer fire rate for 5s |

### 👤 Account System
- Register & sign in with a username and password
- Progress saved **per user account** — XP, levels, gems, upgrades all persist
- Auto-login on return visits
- Guest mode available for quick play

### 🎖️ Commander Progression
Level up from **Recruit → Mythic** across 12 ranks, unlocking new towers, heroes and abilities as you grow.

### 👾 Enemies
Scouts, Warriors, Giants, Harpies, Trolls, Ghosts, Golems, Bosses and Mega Bosses — each with unique HP, speed, armor, and flying properties.

---

## 🕹️ How to Play

1. **Register** or sign in (or play as Guest)
2. Choose a **World** from the home screen
3. Select a **Level**
4. **Place towers** on green tiles by selecting from the bottom panel
5. Hit **Send ▶** to launch each wave
6. **Tap a tower** to upgrade or sell it
7. Use **Abilities** tab for emergency powers
8. Survive all waves → **Victory!** 🏆

**Tips:**
- Place towers at **path bends** for maximum coverage
- **Frost + high-damage** towers are a killer combo
- **Sell weak towers** and rebuild in better spots
- Prepare early — boss waves hit hard at levels 4, 8, 12…

---

## 📦 What's in This Repo

```
index.html          ← The entire game (HTML + CSS + JS)
manifest.json       ← PWA manifest (app name, icon, display mode)
sw.js               ← Service worker (offline support)
icon-192.png        ← App icon (192×192)
icon-512.png        ← App icon (512×512)
README.md           ← This file
```

---

## 🛠️ Technical Details

| Detail | Info |
|--------|------|
| Engine | Vanilla HTML5 Canvas |
| Language | JavaScript ES6+ |
| Styling | CSS3 with custom properties |
| Storage | localStorage (per-user keyed saves) |
| PWA | manifest.json + Service Worker |
| Android | APK + AAB via PWABuilder |
| Font | Google Fonts — Cinzel & Nunito |
| Dependencies | **None** |
| Build step | **None** |

---

## 🚀 Deploy Your Own Copy

### Netlify Drop *(easiest)*
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire project **folder** onto the page
3. Get an instant live URL

### GitHub Pages
1. Push all files to a GitHub repo
2. Go to **Settings → Pages → Deploy from main branch**
3. Live at `https://yourusername.github.io/repo-name`

---

## 📱 Building the Android APK Yourself

This project is PWA-ready. To generate your own APK:

1. Host the project on any static host (Netlify, GitHub Pages, etc.)
2. Go to [pwabuilder.com](https://pwabuilder.com)
3. Paste your hosted URL
4. Click **Package for Stores → Android**
5. Download your APK or AAB

> **Note:** Keep your `signing.keystore` file safe! You'll need it to publish future updates to the Google Play Store.

---

## 🤝 Contributing

Ideas for future updates:
- ☁️ Cross-device cloud saves (Supabase / Firebase)
- 🏆 Global leaderboard
- 🎵 Sound effects and music
- 🌍 More worlds and level layouts
- 🗼 New tower and hero types
- 📊 Google Play Store listing

Fork the repo, make your changes, and open a pull request — all welcome!

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Built with ❤️ using [Claude AI](https://claude.ai) by Anthropic — proving anyone can ship a real game! ⚔️🏰*
