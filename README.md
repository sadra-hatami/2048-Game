<div align="center">

# 2048 Game
# 🔢

### A C++ console version of the sliding-tile game

A 4×4 board in the terminal. Slide the tiles, merge equals, and keep going until no move is left.

<br>

# 👨‍💻 **Sadra Hatami**

### *Developer • Software Engineer • Creator*

<br>

[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Console](https://img.shields.io/badge/Interface-Console-2C3E50?style=for-the-badge)](https://en.wikipedia.org/wiki/Command-line_interface)
[![Game](https://img.shields.io/badge/Genre-Puzzle-8E44AD?style=for-the-badge)](https://en.wikipedia.org/wiki/2048_(video_game))
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/license/mit)
![Open Source](https://img.shields.io/badge/Open_Source-Project-black?style=for-the-badge&logo=github)
[![Stars](https://img.shields.io/github/stars/sadra-hatami/2048-Game?style=for-the-badge)](https://github.com/sadra-hatami/2048-Game/stargazers)

<br>

[🌐 GitHub Profile](https://github.com/sadra-hatami)
•
[📧 Email](mailto:sadra.hatami.1732@gmail.com)

</div>

---

# 📑 Table of Contents

- [About](#-about)
- [Why This Project?](#-why-this-project)
- [Key Features](#-key-features)
- [How to Play](#-how-to-play)
- [Project Structure](#-project-structure)
- [Technologies](#️-technologies)
- [Build](#-build)
- [Usage](#️-usage)
- [Notes](#-notes)
- [FAQ](#-faq)
- [Contact](#-contact)
- [License](#-license)
- [Support](#-support)

---

# 📖 About

**2048 Game** is a console puzzle written in C++.

The board is 4×4. Arrow keys slide every tile in one direction. Two tiles with the same value merge into the next value. A new tile appears after a real move. The round ends when no slide can change the board.

> **Tagline:** *A C++ console version of the 2048 sliding-tile game.*

---

# 🚀 Why This Project?

2048 is a small game with a clear loop: read a key, move a grid, merge equals.

This version keeps that loop in one file:

- A 4×4 board
- Arrow-key controls
- Esc to quit
- A game-over line when the board is stuck

It is a study game, not a scored arcade build.

---

# ✨ Key Features

- 🔢 4×4 board
- ⬆️ Arrow keys for up, down, left, and right
- ➕ Merge of equal tiles
- 🆕 A new tile after a move
- ⎋ Esc to quit
- 💻 Console only

---

# 🎮 How to Play

1. Run the game.
2. Press any key to continue.
3. Slide with the arrow keys.
4. Press Esc to quit.

The game prints `GAME OVER!!` when no move remains. This build does not keep a score and does not stop on a 2048 tile.

---

# 📁 Project Structure

```text
2048-Game/
├── 2048-Game.cpp
└── README.md
```

`2048-Game.cpp` is the whole game. Do not commit a compiled `.exe`.

---

# 🛠️ Technologies

- C++
- Console input for arrow keys
- No extra packages

---

# 🚀 Build

```bash
git clone https://github.com/sadra-hatami/2048-Game.git
cd 2048-Game
g++ 2048-Game.cpp -o 2048
./2048
```

On Windows, MinGW can build the same file. Arrow keys in this program use the Windows key codes, so the intended run is a Windows console.

---

# ▶️ Usage

```bash
./2048
```

`Press Esc anytime to quit the game` is shown at the start.

---

# 📝 Notes

- There is no save file. Closing the program clears the board.
- There is no high score in this build.
- Related playable projects: [Snake Game](https://github.com/sadra-hatami/Snake-Game) and [Arcade Games Website](https://github.com/sadra-hatami/Arcade-Games-Website).

---

# ❓ FAQ

### Does it save the board?

No.

### Does it track score?

No. The round ends when the board cannot move.

### Is this a website?

No. It is a terminal game.

---

# 📬 Contact

**Developer:**

### Sadra Hatami

📧 [Email](mailto:sadra.hatami.1732@gmail.com)

🌐 [GitHub](https://github.com/sadra-hatami)

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If this game is useful as a study sample, please consider giving it a ⭐ on GitHub.

---

<div align="center">

## Designed & Developed with ❤️ for the developer community of Iran and the world by **Sadra Hatami**

</div>
