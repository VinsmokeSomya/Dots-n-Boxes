# ⬜ Dots & Boxes

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![Made with Pygame](https://img.shields.io/badge/Made%20with-Pygame-1f425f.svg)](https://www.pygame.org)

A simple implementation of the classic paper-and-pencil game "Dots and Boxes" using the Pygame library.

---

## ✨ Features

*   Classic Dots & Boxes gameplay.
*   Two-player turn-based system.
*   Visual indication of claimed boxes and scores.
*   Simple and clear interface.
*   Restart and Quit options.

---

## 🚀 Getting Started

### Prerequisites

*   Python 3.x
*   Pygame library:
    ```bash
    pip install pygame
    ```

### Installation & Running

1.  Clone the repository (or download `main.py`).
2.  Navigate to the `Dots & Boxes` directory:
    ```bash
    cd path/to/"Dots & Boxes"
    ```
3.  Run the game:
    ```bash
    python main.py
    # Or if the path has spaces:
    # python "Dots & Boxes/main.py"
    ```

---

## 🎮 How to Play

1.  **Objective:** The goal is to complete more boxes than your opponent.
2.  **Turns:** Players take turns connecting two adjacent dots with a horizontal or vertical line.
3.  **Controls:**
    *   **Click** on a cell area to select it.
    *   Use the **Arrow Keys** (Up, Down, Left, Right) to attempt to draw a line on the corresponding side of the selected cell.
4.  **Claiming Boxes:** If drawing a line completes the fourth side of a box, the player claims that box (marked with their symbol/color) and gets another turn.
5.  **Winning:** The game ends when all dots are connected. The player who claimed more boxes wins.
6.  **Game Options:**
    *   Press `R` to restart the game at any time.
    *   Press `Q` or `Esc` to quit.

---

## 🖼️ Gameplay Screenshot

![Screenshot 2025-05-04 204917](https://github.com/user-attachments/assets/40f85a79-1833-4ebd-b230-8e11213b866f)

