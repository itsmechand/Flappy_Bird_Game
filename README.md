# 🐦 Flappy Bird Game

A web-based clone of the classic Flappy Bird game built using **HTML**, **CSS**, **Bootstrap**, and **JavaScript**. The player controls a bird and must navigate through a series of pipes by clicking or tapping to flap upward, avoiding collisions to achieve a high score.

## 📌 Overview

This project replicates the core gameplay mechanics of the original Flappy Bird game:

- The bird moves upwards on click/tap and is pulled down continuously by gravity.
- The objective is to pass through as many pipe gaps as possible without hitting obstacles.
- The game ends when the bird hits a pipe or touches the ground.

## 🎮 Features

- **🕹️ User Control**: Click or tap to flap and control the bird's upward movement.
- **🌍 Gravity & Collision Detection**: Realistic falling motion and collision logic to end the game.
- **🧱 Pipe Generation**: Pipes appear at random heights with gaps to navigate through.
- **🏆 Scoring System**: Score increases each time the bird successfully passes through pipes.
- **🛑 Game Over Screen**: Displays a message and final score upon game end.
- **🔁 Restart Game Option**: Allows the user to restart the game after it ends.
- **📱 Responsive Design**: Built with Bootstrap for seamless play on mobile, tablet, and desktop.

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML**   | Structure of the game page |
| **CSS**    | Visual styling for bird, pipes, background, etc. |
| **Bootstrap** | Responsive layout and mobile support |
| **JavaScript** | Game logic, physics (gravity, velocity), event handling |

## 🔍 Implementation Details

### ✅ User Control
- Click or tap events make the bird "flap" (jump up).
- Gravity is applied continuously to pull the bird downward.

### ✅ Gravity & Collision
- Gravity increases the bird's vertical velocity over time.
- Collision is detected when the bird:
  - Hits a pipe
  - Touches the ground or top of the screen

### ✅ Pipe Generation
- Pipes are generated at intervals with randomized vertical gaps.
- Pipes scroll leftward to simulate bird motion.

### ✅ Scoring System
- The score is incremented when the bird passes through a pipe pair.
- Each pipe tracks whether it’s already been counted.

### ✅ Responsive Design
- Designed to work across devices using Bootstrap.
- Tap or keypress input supported.

## 📷 Screenshots

_Add screenshots here if available (e.g., gameplay, game over screen)._

