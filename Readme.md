# 🐍 Snake Food Hunt

A classic, retro-style Snake game built with pure **HTML, CSS, and JavaScript**. This project features smooth grid-based movement, persistent high scores using LocalStorage, and immersive sound effects.

## 🚀 Live Demo
You can play the game here: [https://pariagrawal1234.github.io/Snake-Food-Game/](https://pariagrawal1234.github.io/Snake-Food-Game/)

## 🎮 How to Play
- Use the **Arrow Keys** (Up, Down, Left, Right) to control the snake.
- Eat the **Food** to grow longer and increase your score.
- **Avoid** hitting the walls or your own tail, or it's Game Over!
- Your **High Score** is saved automatically, so you can try to beat it every time you return.

## ✨ Features
- **Responsive Design:** The game board uses `vmin` units to look great on both mobile and desktop screens.
- **Persistent Data:** Uses `window.localStorage` to keep track of your best score even after refreshing the page.
- **Dynamic Rendering:** Built using a JavaScript game loop with `requestAnimationFrame` for smooth performance.
- **Sound Effects:** Includes background music and interactive sounds for eating and collisions.

## 🛠️ Technologies Used
- **HTML5:** Semantic structure and game board container.
- **CSS3:** Flexbox and Grid layout for perfect centering and snake styling.
- **JavaScript (Vanilla):** Game logic, collision detection, and DOM manipulation.

## 📂 Project Structure
```text
├── css/
│   └── style.css       # Game styling and layout
├── js/
│   └── index.js       # Core game logic and High Score system
├── music/             # Sound effects and background tracks
├── index.html         # Main game entry point
└── README.md          # Project documentation