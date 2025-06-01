
# 🐍 Snake Game
![Screenshot (67)](https://github.com/user-attachments/assets/2592de62-2a22-4b1e-b6e2-9ecb05720112)

A classic Snake Game built using **HTML**, **CSS**, and **JavaScript**. The game includes features like scoring, increasing speed, food generation, collision detection, and persistent high scores using local storage.

## 🎮 Features

- Real-time gameplay using `requestAnimationFrame`
- Dynamic food spawning
- Snake grows when food is eaten
- Speed increases as score increases
- Collision detection with self and walls
- High score tracking using `localStorage`
- Audio effects for food and game over

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## 📦 How to Run

1. **Clone or Download the repository**
2. Open the `index.html` file in any modern browser

> No server setup or npm install required

## 🔁 Controls
![Screenshot (68)](https://github.com/user-attachments/assets/1d58b6c5-3341-4ac0-a9d2-b014d6363b83)

- `Arrow Up` - Move Up
- `Arrow Down` - Move Down
- `Arrow Left` - Move Left
- `Arrow Right` - Move Right

> Movement prevents reversing directly into itself

## 🧠 Game Logic Overview
![Uploading Screenshot (69).png…]()

- **Snake Movement**: Controlled via arrow keys and `inputDirection` logic
- **Collision Detection**: Ends game if snake hits wall or itself
- **Food Generation**: Random position on grid; new food generated after eating
- **Score Management**: Score increases on eating; high score saved in browser storage
- **Restart Functionality**: Clicking reset button reloads the game

## 🔊 Audio

Place the following sound files in a `music/` folder:
- `food.mp3`
- `gameover.mp3`
- `music.mp3`

## 🚀 Future Improvements

- Mobile touch controls
- Difficulty levels
- Pause/Resume functionality

## 📄 License

This project is open-source and available for any use.
