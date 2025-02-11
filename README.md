# 2048 Game

## 🧩 Overview
The 2048 game is a single-player sliding puzzle game where the goal is to combine numbered tiles on a 4x4 grid to create a tile with the value of 2048. The game ends when there are no more valid moves or when a tile with the value of 2048 is created.

This implementation of the 2048 game is built with JavaScript, HTML, and CSS, and allows players to interact with the game using the arrow keys.

## 🔑 Features

- **4x4 Grid**: The game field consists of a 4x4 grid where tiles can move in four directions (up, down, left, right).
- **Tile Merging**: Identical tiles merge to form a new tile with double the value (e.g., two 2 tiles become a 4 tile).
- **Random Tile Generation**: After each valid move, a new tile (2 or 4) appears randomly in an empty cell.
- **Winning Condition**: The game displays a win message when a tile reaches 2048.
- **Game Over**: The game ends when there are no available moves, and a "Game Over" message is displayed.
- **Score Tracking**: The score increases with every merged tile, and the final score is displayed at the end.

## 🌐 Live Demo

You can try out the game by visiting the live demo here:

[**DEMO LINK**](https://anna-agerone.github.io/2048-game/)

## 🎮 How to Play

1. Use the arrow keys (⬆️⬇️⬅️➡️) to move the tiles.
2. Tiles of the same number will merge when moved together.
3. The goal is to create a tile with the value of 2048.
4. The game ends when there are no valid moves left or when you win.

## 🛠️ Technologies Used

**JavaScript**: For game logic and interactivity.
**HTML**: For structuring the game layout.
**CSS**: For styling and design.

## ⚙️ Installation & Prerequisites

1. Ensure that you have [Node.js](https://nodejs.org/) installed. This project requires Node.js version 14 or higher. You can check your Node.js version using:
   ```bash
   node -v

2. Clone the repository:

git clone https://github.com/anna-agerone/2048-game.git

3. Navigate into the project directory:

cd 2048-game

4. Install the project dependencies:

npm install

5. Start the Game
Once you've installed the dependencies, you can start the project using the following commands:

npm start

🚀 This will launch the game and open it in your default web browser.

🎉 Enjoy the game, and good luck reaching 2048! 🎮



