
---

# 🐍 Snake Game

A classic Snake Game built with **HTML**, **CSS**, and **JavaScript**! This responsive game allows you to play on both desktop and mobile devices. Keep track of your **score** and **high score** as you navigate the snake, collect food, and try to avoid collisions.

## 🚀 Features

- **Responsive Design:** Works smoothly on both desktop and mobile devices.
- **Score Tracking:** Displays your current score and stores your high score using `localStorage`.
- **Keyboard & Touch Controls:** Use arrow keys on desktop or on-screen buttons for mobile.
- **Dynamic Gameplay:** Snake grows as you collect food, and the speed remains consistent for a challenging experience.

## 📂 Project Structure

```
snake-game/
├── index.html        # Game structure and layout
├── style.css         # Styling for the game board and UI
└── script.js         # Game logic and functionality
```

## 🛠️ Technologies Used

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" width="50" height="50"/> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" width="50" height="50"/> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="50" height="50"/>
</p>

- **HTML5** – Structure of the game
- **CSS3** – Styling and responsive design
- **JavaScript (ES6)** – Game logic and interactivity

## 🎮 How to Play

1. **Start the Game:** The game starts automatically when you open the page.
2. **Controls:**
   - **Desktop:** Use **Arrow Keys** to navigate the snake.
   - **Mobile:** Tap the arrow icons to control the snake's direction.
3. **Objective:** Collect the red food blocks to grow the snake. The game ends if the snake hits the walls or itself.
4. **High Score:** Your highest score is saved in your browser's local storage.

## 🧑‍💻 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sanskar-2104/snake-game.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd snake-game
   ```

3. **Open `index.html` in your browser:**
   - Double-click on the `index.html` file.
   - Or use a live server in your code editor.

## 🔧 Customization

- **Change the Grid Size:** Modify the `grid-template` in `style.css` to adjust the game board dimensions.
- **Adjust Speed:** Change the interval time in `script.js`:
  ```javascript
  setInterval(initGame, 125); // Lower value = faster speed
  ```

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 🙌 Acknowledgements

- Icons by [FontAwesome](https://fontawesome.com/)
- Inspired by the classic Snake game we all love!

---
