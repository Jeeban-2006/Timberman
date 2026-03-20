# 🌲 Timberman Game (C++ | SFML)

![C++](https://img.shields.io/badge/C++-17-blue?style=for-the-badge\&logo=c%2B%2B)
![SFML](https://img.shields.io/badge/SFML-2.5-green?style=for-the-badge)
![Game](https://img.shields.io/badge/Type-2D%20Arcade-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

> A fast-paced 2D arcade game inspired by **Timberman**, built using **C++ and SFML**. Test your reflexes by chopping wood while avoiding deadly branches!



## 🚀 Features

* ⚡ Smooth real-time gameplay
* 🎯 Progressive difficulty system
* ⏱️ Dynamic time bar mechanics
* 🎵 Sound effects for immersive experience
* 🎨 Simple and clean 2D visuals
* 🧠 Reflex-based challenge gameplay

---

## 🕹️ Controls

| Key            | Action            |
| -------------- | ----------------- |
| ⬅️ Left Arrow  | Move Left & Chop  |
| ➡️ Right Arrow | Move Right & Chop |
| ❌ Close Window | Exit Game         |

---

## 🧠 Game Mechanics

* Player chops a tree from either side
* Random branches spawn as obstacles
* Collision with branch = **Game Over** 💀
* Score increases with each successful chop
* Time bar decreases continuously
* Faster gameplay as score increases

---

## 🏗️ Tech Stack

* **Language:** C++
* **Library:** SFML (Simple and Fast Multimedia Library)
* **Core Concepts:**

  * Game Loop
  * Event Handling
  * Collision Detection
  * Sprite Rendering
  * Real-time Input Processing

---

## 📂 Project Structure

```bash
Timberman/
│
├── Timberman.cpp              # Main game logic
│
├── assets/
│   ├── graphics/           # Images & textures
│   │   ├── background.png
│   │   ├── tree.png
│   │   ├── player.png
│   │   └── branch.png
│   │
│   ├── sound/              # Sound effects
│   │   ├── chop.wav
│   │   ├── death.wav
│   │   └── out_of_time.wav
│   │
│   └── fonts/
│       └── font.ttf
│
├── build/                  # Compiled files (optional)
│
├── screenshots/            # Screenshots / GIFs
│   └── gameplay.png
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔧 Prerequisites

* C++ Compiler (GCC / MSVC)
* SFML Library (>= 2.5)

🔗 Download SFML: https://www.sfml-dev.org/download.php

---

### 🛠️ Run on Windows (Visual Studio)

1. Clone repository:

```bash
git clone https://github.com/Jeeban-2006/Timberman.git
cd Timberman
```

2. Open project in Visual Studio

3. Configure SFML:

   * Add **Include Directory**
   * Add **Library Directory**
   * Link these libraries:

```txt
sfml-graphics.lib
sfml-window.lib
sfml-system.lib
sfml-audio.lib
```

4. Build & Run 🚀

---

### 🐧 Run on Linux

```bash
g++ Timber.cpp -o timber -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./timber
```

---

## 📈 Future Improvements

* 🎮 Main Menu UI
* 🏆 High Score Saving System
* 🌄 Multiple Themes & Environments
* 🧍 Character Animations
* 🔥 Power-ups (shield, slow time, etc.)
* 📱 Cross-platform build

---

## 🤝 Contributing

Contributions are welcome!

```bash
1. Fork the repository
2. Create a new branch (feature-name)
3. Commit your changes
4. Push and open a Pull Request
```

---

## 📜 License

This project is created for **educational and learning purposes**.

---

## 👨‍💻 Author

**Jeeban Krushna Sahu**

* 🎓 B.Tech Student
* 💡 Interested in Game Development & AI
* 🚀 Building impactful projects

---

## ⭐ Support

If you like this project:

* ⭐ Star this repo
* 🍴 Fork it
* 📢 Share it

---

## 💡 Inspiration

Inspired by the classic Timberman arcade game — simple yet addictive gameplay focused on speed and reflex.

---


