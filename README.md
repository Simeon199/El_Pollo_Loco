# El Pollo Loco – The Web Browser Jump And Run Game

A web browser jump and run game that was realized with object oriented JavaScript.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Technologies](#technologies)
- [Installation](#installation)
- [How to Use It](#how-to-use-it)

---

## About the Project

El Pollo Loco is a web browser jump and run game designed and built as part of a web development bootcamp at the Developer Akademie. It is therefore not intended for commercial use and was created solely for private testing and learning purposes.

---

## Technologies

- HTML
- CSS
- Vanilla JavaScript

---

## Installation

The game logic is written in plain Vanilla JavaScript, but a build step is required to bundle and minify the source files before opening the game. Make sure you have [Node.js](https://nodejs.org) installed.

1. Clone the repository:
   ```bash
   git clone https://github.com/Simeon199/El_Pollo_Loco.git
   ```
2. Move to the project directory:
   ```bash
   cd El_Pollo_Loco
   ```
3. Install the build dependencies:
   ```bash
   npm install
   ```
4. Run the bundler to generate the required files in `dist/`:
   ```bash
   npm run build
   ```
5. Open `index.html` directly in your browser – that's it!

---

## How to Use It

You are controlling the main character **Pepe Peligroso** who has to defeat a large number of attacking chickens by throwing items at them or jumping on them.

### 🎮 Controls

| Key     | Action                                                                     |
| ------- | -------------------------------------------------------------------------- |
| `SPACE` | ⬆️ Jump – leap into the air to avoid attacking chickens or to jump on them |
| `→`     | ➡️ Move right                                                              |
| `←`     | ⬅️ Move left                                                               |
| `D`     | 🍾 Throw – hurl a bottle at the attacking chickens                         |

### How to Win

- Defeat **all enemies** to win the game.
- ⚠️ Watch out for the **final boss**! He will charge at you and try to drive you away when you get too close.
- The final boss will also attack when all other enemies are defeated or when you strike him first.

Good luck and have fun! 🐔🎉
