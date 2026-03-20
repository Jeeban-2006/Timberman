🌲 Timberman Game (C++ | SFML)

A fast-paced 2D arcade-style game inspired by the classic Timberman, built using C++ and SFML. Chop wood, avoid branches, and survive as long as possible!

🎮 Demo Preview

(Add screenshots or gameplay GIFs here)

📸 Example:
![Gameplay](screenshots/gameplay.png)
🚀 Features

⚡ Smooth real-time gameplay using SFML

🎯 Increasing difficulty as score grows

⏱️ Dynamic time bar system

🎵 Sound effects and game feedback

🎨 Simple yet engaging 2D graphics

🧠 Reflex-based mechanics (easy to learn, hard to master)

🕹️ Game Controls
Key	Action
⬅️ Left Arrow	Move left & cut
➡️ Right Arrow	Move right & cut
❌ Close Window	Exit game
🧠 Game Logic

Player chops a tree from left or right side

Random branches appear as obstacles

If player hits a branch → 💀 Game Over

Score increases with each successful cut

Time bar decreases continuously but:

⬆️ Increases slightly with higher score

🏗️ Tech Stack

Language: C++

Library: SFML (Simple and Fast Multimedia Library)

Concepts Used:

Game Loop

Event Handling

Collision Detection

Sprite Rendering

Real-time Input Processing

📦 Project Structure
Timberman/
│
├── Timber.cpp        # Main game logic
├── graphics/         # Game textures & sprites
├── sound/            # Audio files
├── fonts/            # UI fonts
├── Debug/Release     # Build outputs
└── README.md
⚙️ Installation & Setup
🔧 Prerequisites

C++ Compiler (GCC / MSVC)

SFML Library (>= 2.4)

Download SFML 👉 https://www.sfml-dev.org/

🛠️ Build Steps (Windows - Visual Studio)

Clone the repository:

git clone https://github.com/Jeeban-2006/Timberman.git
cd Timberman

Open .sln or project file in Visual Studio

Configure SFML:

Add SFML include directory

Add SFML lib directory

Link libraries:

sfml-graphics.lib
sfml-window.lib
sfml-system.lib
sfml-audio.lib

Build and Run 🚀

🐧 Build (Linux)
g++ Timber.cpp -o timber -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./timber
📈 Future Improvements

🧍 Character animations

🌄 Multiple environments/themes

🏆 High-score saving system

🎮 Game menu UI

📱 Cross-platform support

🔥 Power-ups & advanced mechanics

🤝 Contributing

Contributions are welcome!

Fork the repo

Create a new branch

Make your changes

Submit a Pull Request

📜 License

This project is for learning and educational purposes.

👨‍💻 Author

Jeeban Krushna Sahu

🎓 B.Tech Student

💡 Passionate about Game Dev & AI

🚀 Building impactful projects

⭐ Show Your Support

If you like this project:

🌟 Star the repository

🍴 Fork it

📢 Share it

💡 Inspiration

Inspired by the classic Timberman arcade concept — simple mechanics, addictive gameplay, and fast reflex challenges.
