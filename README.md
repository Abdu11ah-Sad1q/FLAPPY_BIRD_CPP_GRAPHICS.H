# Flappy Bird Clone (C++)

A classic, retro-style Flappy Bird clone built using C++ and the BGI (Borland Graphics Interface) library. This project demonstrates basic game development principles, including real-time rendering, collision detection, and file-based score tracking.

## 🚀 Features

*   **Classic Gameplay**: Navigate the bird through moving pipe obstacles.
*   **Leaderboard System**: Track high scores for different players using local file persistence (`data.txt`).
*   **Simple Input**: Intuitive single-key control to keep the bird in the air.
*   **Procedural Obstacles**: Randomly generated pipe heights for endless playability.

## 🛠 Prerequisites

To compile and run this project, you will need:
*   **Compiler**: A C++ compiler that supports the `graphics.h` library (e.g., Turbo C++, Dev-C++ with MinGW, or Code::Blocks).
*   **Graphics Library**: `graphics.h` (BGI) must be correctly configured in your development environment.

## 📋 How to Play

1.  **Start**: Run the executable.
2.  **Navigate**: Use the main menu to choose:
    *   **G**: Start Game
    *   **L**: View Leaderboard
    *   **Q**: Quit
3.  **Controls**: Press the **Spacebar** to make the bird jump.
4.  **Objective**: Avoid hitting the pipes or the top/bottom boundaries of the screen to achieve the highest score.

## 💾 Data Persistence

The game stores player scores in a file named `data.txt`. This file is automatically created in the project directory when you finish your first game session.

## 🤝 Contributing

This is a student-level project intended for learning and demonstration. Feel free to fork, modify, and improve the codebase. Suggestions for improvement:
*   Adding sound effects.
*   Implementing a more modern rendering library (e.g., SFML or SDL).
*   Improving the collision detection algorithm.

## 📜 License

This project is open-source. Feel free to use the code for educational purposes.
