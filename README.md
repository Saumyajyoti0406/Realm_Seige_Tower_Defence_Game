# 🏰 Realm Siege — Strategic Tower Defense

> A fully featured, mobile-first tower defense game built in a **single HTML file** — no frameworks, no dependencies, no build step required.

![Game Preview](https://img.shields.io/badge/Platform-Browser%20%7C%20Mobile-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Size](https://img.shields.io/badge/Size-Single%20HTML%20File-gold?style=flat-square)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=flat-square)

---

## 🎮 Play Now

Open `realm-siege-v4.html` in any modern browser — that's it. No installation, no server, no npm.

---

## 📖 About

Realm Siege is a rich tower defense game where you defend your realm against waves of increasingly powerful enemies across multiple worlds. Place towers, deploy heroes, unleash powerful abilities, and upgrade your defenses to survive every onslaught.

The game features a full **commander progression system**, a **persistent account system** with per-user saves, and 32 hand-crafted campaign levels across 4 distinct worlds.

---

## ✨ Features

### 🗺️ Campaign
- **4 unique worlds** — Verdant Forest, Scorched Sands, Lava Fields, and Frozen Peaks
- **8 levels per world** (32 total), including boss encounters every 4th level
- Star rating system (1–3 stars) based on lives remaining
- Progressive difficulty that ramps across worlds and levels
- **Beginner-friendly** — the first 3 levels feature extra starting gold, bonus lives, and reduced enemy counts to ease new players in

### 🏗️ Towers
| Tower | Unlock | Special |
|-------|--------|---------|
| 🏹 Archer | Level 1 | Balanced, high rate of fire |
| 💣 Cannon | Level 2 | AoE splash damage |
| 🔮 Magic | Level 4 | Ignores enemy armor |
| ❄️ Frost | Level 6 | Slows enemies |
| ☠️ Poison | Level 8 | Damage-over-time DoT |
| ⚡ Tesla | Level 12 | Chain lightning strikes |

Each tower has a **3-tier upgrade tree** with branching paths at tier 3, giving you meaningful strategic choices (e.g., Archer → Barrage for rapid fire *or* Sniper for armor-piercing).

### 🧝 Heroes
Deploy powerful hero units that fight alongside your towers:
- **Lyra** 🧝 — Root & gold aura (unlocked from the start)
- **Kael** 🧙 — Fireball AoE specialist
- **Serafin** 🧊 — Blizzard aura support

### ⚡ Abilities
Unleash powerful timed abilities to turn the tide of battle:
- ❄️ **Freeze** — Freeze all enemies for 3 seconds
- ⚡ **Storm** — Chain lightning hits 10 enemies
- ☄️ **Meteor** — Massive AoE explosion
- ⏳ **Time Warp** — Double game speed for 8 seconds
- 🏹 **Barrage** — Triple archer fire rate for 5 seconds

### 👤 Account System
- **Register & Sign In** with a username and password
- Progress (XP, level, completed levels, gems, upgrades) is **saved per user account**
- **Auto-login** on return visits — jump straight back into your game
- **Guest mode** available for casual play (no saves)
- Accounts are stored locally in the browser — no server needed

### 🛒 Shop & Permanent Upgrades
Spend gems earned from completing levels on permanent passive upgrades:
- 💹 Merchant Guild — +10% gold per kill
- 🧱 Wall Fortify — +5 starting lives
- 🔭 Watchtower — +8% tower range
- ⚒️ Forge Master — +10% tower damage
- 🌀 Arcane Focus — -15% ability cooldowns
- 👑 Royal Treasury — +50 starting gold

### 🎖️ Commander Progression
Level up your Commander rank by earning XP in battle to unlock new towers, abilities, and heroes:

| Level | Title | Unlock |
|-------|-------|--------|
| 1 | Recruit | Archer, Lyra |
| 2 | Soldier | Cannon Tower |
| 3 | Veteran | Freeze Ability |
| 4 | Knight | Magic Tower |
| 5 | Captain | Storm Ability |
| 6 | Commander | Frost Tower |
| 7 | Warlord | Meteor Ability |
| 8 | Champion | Poison Tower |
| 9 | Grand Knight | Kael & Serafin Heroes |
| 10 | Grand Warlord | Time Warp Ability |
| 11 | Archon | Barrage Ability |
| 12 | Mythic | Tesla Tower |

### 👾 Enemy Types
| Enemy | Trait |
|-------|-------|
| 🐀 Scout | Fast, low HP |
| ⚔️ Warrior | Armored brawler |
| 👾 Giant | Slow but tanky |
| 🦅 Harpy | Flying unit |
| 🧟 Troll | Tough regenerator |
| 👻 Ghost | Armored flying unit |
| 🗿 Golem | High armor, massive HP |
| 🐉 Boss | Unique boss encounter |
| 👹 Mega Boss | End-game challenge |

---

## 🕹️ How to Play

1. **Register** or sign in (or play as guest)
2. Choose a **World** from the home screen
3. Select a **Level** to start
4. **Place towers** on green tiles by selecting a tower from the bottom panel, then tapping a valid cell
5. Hit **Send ▶** to start each wave
6. **Upgrade or sell** towers by tapping them during play
7. Use **Abilities** from the Abilities tab for emergency situations
8. Survive all waves to **Victory!** 🏆

### Tips
- Place towers at **bends in the path** for maximum coverage
- **Frost towers** pair well with high-damage towers — slow enemies, then burst them down
- Save gold between waves to afford key upgrades
- **Sell underperforming towers** to reinvest gold in better positions
- Boss waves always appear at levels 4, 8, 12, etc. — prepare ahead

---

## 🗂️ Project Structure

```
realm-siege-v4.html   ← The entire game (HTML + CSS + JS, ~1,400 lines)
README.md             ← This file
```

Everything lives in a single self-contained HTML file:
- **CSS** — Custom design system with CSS variables, animations, and a mobile-first responsive layout
- **Canvas rendering** — Vanilla Canvas 2D API for all game visuals
- **Game logic** — Pure vanilla JavaScript, no libraries
- **Persistence** — localStorage for per-user save data

---

## 🛠️ Technical Details

| Detail | Info |
|--------|------|
| Engine | Vanilla HTML5 Canvas |
| Language | JavaScript (ES6+) |
| Styling | CSS3 with custom properties |
| Storage | localStorage (per-user keyed saves) |
| Font | Google Fonts — Cinzel + Nunito |
| Dependencies | **None** |
| Build step | **None** |
| File count | **1** |

---

## 🚀 Deployment

Because the game is a single HTML file, deployment is trivially easy:

### Netlify Drop *(fastest — 30 seconds)*
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `realm-siege-v4.html` onto the page
3. Get an instant public URL

### GitHub Pages
1. Rename the file to `index.html`
2. Push to a GitHub repository
3. Go to **Settings → Pages** and set source to the main branch
4. Your game will be live at `https://yourusername.github.io/realm-siege`

### Vercel
```bash
npx vercel --prod
```

### Self-hosted
Simply serve the HTML file with any static file server:
```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```

---

## 📱 Mobile Support

Realm Siege is designed mobile-first:
- Touch input fully supported (tap to place, tap to select)
- Responsive layout capped at 480px wide, centered on larger screens
- `user-scalable=no` viewport to prevent accidental zoom during play
- Hardware-accelerated Canvas rendering

---

## 🔒 Account & Save Data

Player accounts and save data are stored **entirely in the browser's localStorage**. This means:
- ✅ No server, no database, no sign-up emails
- ✅ Instant account creation
- ✅ Works fully offline
- ⚠️ Progress is tied to the specific browser/device
- ⚠️ Clearing browser data will erase saves

Passwords are hashed before storage. This is a lightweight local hash — suitable for a game, but **not intended for sensitive data**.

---

## 🤝 Contributing

Contributions are welcome! Some ideas for extensions:
- 🌍 Additional worlds and level layouts
- 🗼 New tower types (e.g., ballista, flame thrower)
- 🧙 Additional hero units with unique abilities
- 🏆 Leaderboard / high score system
- ☁️ Cloud save support via Supabase or Firebase
- 🌐 Multiplayer co-op mode

To contribute, fork the repo, make your changes to the HTML file, and open a pull request.

---

## 📄 License

MIT License — free to use, modify, and distribute. See `LICENSE` for details.

---

## 🙏 Credits

- Fonts: [Google Fonts](https://fonts.google.com) — Cinzel & Nunito
- Emoji artwork: System emoji (platform-native)
- Built with: Pure vanilla HTML, CSS, and JavaScript — no external game engine

---

*Made with ❤️ — defend your realm, commander!* ⚔️
