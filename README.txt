# Menagerie Match

### 🐾 Description:
Menagerie Match is a vibrant and interactive match-3 puzzle game built using C++ and SFML (Simple and Fast Multimedia Library). Inspired by games like Bejeweled and Candy Crush, this game tasks players with matching adorable animal tiles on an 8x8 grid to earn points and unlock victory screens.

There are two levels with distinct challenges:
- **Level 1**: Limited to 30 moves — a race to maximize your score within a move constraint.
- **Level 2**: Time-limited (120 seconds) — score as high as possible before the timer runs out.

Features include:
- 7 animal types: Bear, Bunny, Koala, Cat, Raccoon, Dog, and Fox.
- Tile-matching logic for vertical and horizontal matches.
- Score tracking and individual animal match counts.
- Win/Lose conditions based on performance.
- Soundtrack playback with SFML Audio.
- Custom visuals and a clean UI using SFML graphics.

---

### ▶️ How to Run the Game:

#### 📌 Prerequisites:
- **C++ compiler (e.g., g++, clang++)**
- **SFML 2.x** installed on your system (https://www.sfml-dev.org/download.php)

#### 💻 Compilation Instructions:

Make sure you are in the project root directory and run the following command:

```bash
g++ MenagerieMatch.cpp -o MenagerieMatch -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
```

> Note: You may need to specify paths to SFML include/library folders using `-I` and `-L` flags if not globally installed.

#### ▶️ To Run:
```bash
./MenagerieMatch
```

Ensure your executable and the following asset folder structure is in place:
```
Project Root/
├── MenagerieMatch.cpp
├── MenagerieMatch (executable after build)
├── README.txt
└── sprites/
    ├── Title.png
    ├── Menu.png
    ├── Help.png
    ├── YouLose.png
    ├── YouLoseLVL2.png
    ├── YouWin.png
    ├── Background.png
    ├── animals.png
    ├── Calibri.ttf
    └── InGameSong.wav
```

---

### 🎮 Controls:
- **Enter** – Proceed from title screen to menu.
- **1** – Start Level 1 (30 Moves).
- **2** – Start Level 2 (120 Seconds).
- **3** – View Help screen.
- **4** – Highscores (currently a placeholder).
- **Left Mouse Button** – Click to select and swap adjacent animal tiles.
- **Escape** – Exit any window/screen.

---

### 🎯 Objectives:
- Match 3 or more animals horizontally or vertically.
- Score 250 points or more to win.
- Match combinations to increase individual animal counters.
- In Level 1: Use moves wisely.
- In Level 2: Beat the clock.

---

### 🛠️ Notes:
- The game includes dynamic sprite rendering using SFML.
- Match detection is optimized using flags.
- Matching combinations can trigger score multipliers.

---

### 📜 License:
This game is a student/indie project and is free to use and modify. Ensure asset rights before distribution.

---

Enjoy matching with Menagerie Match! 🧩🐾
