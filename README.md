# 👑 N-Queens Chess Puzzle & Interactive Visualizer

[![Live Demo](https://img.shields.io/badge/Live_Demo-Click_Here-brightgreen?style=for-the-badge&logo=githubpages)](https://mr0utkarsh.github.io/n-queens-chess-game/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Tech Stack](https://img.shields.io/badge/Stack-HTML5_%7C_Tailwind_CSS_%7C_JavaScript-blue?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

An interactive, feature-rich web application built to solve, learn, and visualize the classic **N-Queens Problem** using recursive backtracking algorithms. Play manually with real-time collision detection or let the step-by-step automated solver demonstrate algorithmic problem solving.

🚀 **Live Website:** [https://mr0utkarsh.github.io/n-queens-chess-game/](https://mr0utkarsh.github.io/n-queens-chess-game/)

---

## ✨ Key Features

* **♟️ Multiple Board Sizes:** Choose between 4x4 (Easy), 5x5 (Medium), 6x6 (Hard), and 8x8 (Classic) chessboard configurations.
* **🔴 Real-Time Threat Visualization:** Visual conflict indicators highlight illegal queen placements along rows, columns, and diagonals instantaneously.
* **🤖 Step-by-Step Backtracking Visualizer:** Automated solver demonstrates backtracking execution visually with speed control capabilities.
* **💡 Smart Hint & Move History:** Integrated hint generator to find valid placements and full Undo/Redo step history.
* **🎨 Custom Aesthetics & Themes:** Switch dynamically between Classic Wood, Modern Slate, and Emerald board styles.
* **🔊 Synthesized Web Audio SFX:** Built-in audio feedback powered by native browser Web Audio API for piece placements, alerts, and victory sounds.
* **🎉 Victory Celebration:** Interactive modal with dynamic stats tracking (timer, move count) and confetti physics upon puzzle completion.

---

## 🧠 Algorithm & Logic Overview

The **N-Queens Problem** requires placing $N$ chess queens on an $N \times N$ chessboard such that no two queens attack each other.

* **Core Strategy:** Depth-First Search (DFS) with Recursive Backtracking.
* **Time Complexity:** $\mathcal{O}(N!)$ worst-case execution time, optimized via collision array lookup tables.
* **Space Complexity:** $\mathcal{O}(N)$ stack depth.

---

## 🛠️ Tech Stack & Dependencies

| Component | Technology |
| :--- | :--- |
| **Markup Structure** | HTML5 Semantic Elements |
| **Styling & Layout** | Tailwind CSS Framework & Custom CSS Animations |
| **Application Logic** | Vanilla JavaScript (ES6+) |
| **Typography & Icons** | Google Fonts (Inter, Cinzel) & Font Awesome 6.4 |
| **Audio Engine** | Web Audio API |
| **Particles** | Canvas Confetti Library |

---

## 🎮 How to Play

1. Select your target board size ($4 \times 4$ to $8 \times 8$).
2. Click any cell to place or remove a Queen.
3. Ensure no two Queens overlap in the same row, column, or diagonal line.
4. Fill the entire board with $N$ safe Queens to complete the challenge!

---

## 📂 Local Setup & Installation

To run this application locally on your system:

```bash
# 1. Clone this repository
git clone [https://github.com/mr0utkarsh/n-queens-chess-game.git](https://github.com/mr0utkarsh/n-queens-chess-game.git)

# 2. Navigate to project folder
cd n-queens-chess-game

# 3. Open index.html in your web browser
# (No additional build tools or npm installs required)
