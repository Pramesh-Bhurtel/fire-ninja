# 🔥 Fire Ninja | Maka Bosada Aag

**Fire Ninja** is an intense, high-speed arcade slash game built with vanilla JavaScript. Slice through waves of fireballs, collect powerful orbs, and climb the ranks to become the ultimate master of flame: **Maka Bosada Aag**.

---

## 🎮 Game Overview

In Fire Ninja, your mission is simple: **Slice everything except the bombs.** As you progress, you'll earn Power (currency), gain XP to level up, and unlock devastating skills to clear the screen.

### ⚔️ The Mission
- **Slice Fireballs & Stars:** Grow your Power and increase your score.
- **Reach the Top Rank:** Advance from a mere *Spark* to the legendary *Maka Bosada Aag*.
- **Avoid Bombs:** One wrong slice resets your session progress to zero. Only your **High Score** is eternal.

---

## 🚀 Features

- **Dynamic Combo System:** Chain hits to multiply your points. Reach a 15x combo to unleash the **Fire Ultimate**!
- **Progression & Ranks:** Level up by gaining XP. Advance through 5 distinct ranks:
  - ✨ Spark
  - 🔥 Ember
  - ☄️ Blaze
  - 🌋 Inferno
  - 👑 **Maka Bosada Aag**
- **In-Game Shop:** Use your earned Power to buy passive upgrades and active skills.
- **Persistence:** Your level, high score, and upgrades are saved automatically to `localStorage`.
- **Visual Excellence:** Realistic fire textures (SVG filters), particle explosions, and screen-shake effects.

---

## ⌨️ Controls

| Action | Control |
| :--- | :--- |
| **Slash** | Mouse Click & Drag / Touch |
| **Pause & Shop** | `Space` |
| **Fire Nova** | `A` (Level 1+) |
| **Time Freeze** | `S` (Level 5+) |
| **Meteor Shower** | `D` (Level 10+) |
| **Spirit Blade** | `W` (Level 15+) |

---

## 🔮 Mechanics

### Target Types
- **Normal Fireball:** The bread and butter. Provides base points.
- **Golden Star:** Rare and fast. Provides **5x** points of a normal fireball.
- **Bomb:** 💣 **FATAL ERROR.** Slicing a bomb ends your run unless you have a shield.
- **Power-up Orbs:**
  - 🔥 **Fire Boost:** 5x Power gain for 10 seconds.
  - ⏳ **Slow Motion:** Freezes time for 5 seconds.
  - 🛡️ **Shield:** Protects you from one bomb hit.
  - 💥 **Score Burst:** Instant massive XP/Power gain.

### Active Skills
- **Fire Nova:** Obliterates all non-bomb targets on screen instantly.
- **Time Freeze:** Stops all targets in their tracks for 5 seconds.
- **Meteor Shower:** Spawns a rapid wave of 10 targets (no bombs!).
- **Spirit Blade:** Automatically slashes targets as they fall for 5 seconds.

---

## 🛠️ Technical Structure

The project is organized into modular JavaScript files for better maintainability:

- **`index.html`**: The core layout, HUD, and SVG filters.
- **`css/style.css`**: Premium styling, animations, and "Maka Bosada" visual modes.
- **`js/game.js`**: Core state management, progression system, and save/load logic.
- **`js/physics.js`**: The arcade engine handling spawns, gravity, and collision/hit detection.
- **`js/skills.js`**: Logic for all active special abilities.
- **`js/effects.js`**: Handles particles, floating text, and visual feedback.
- **`js/audio.js`**: Adaptive sound engine with pitch-shifting based on combo.

---

## 📦 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pramesh-Bhurtel/Fire-Ninja.git
   ```
2. **Launch:**
   Open `index.html` in any modern web browser. 

> [!TIP]
> For the best experience, use a local server:
> `npx http-server ./`

---

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

