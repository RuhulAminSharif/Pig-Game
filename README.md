# 🎲 Pig Game

A simple 2-player dice game built with HTML, CSS, and JavaScript. This project is inspired by the classic Pig Dice Game and allows two players to take turns rolling a dice, accumulating scores, and trying to reach the winning score first.

[👉 Live Demo](https://ruhulaminsharif.github.io/Pig-Game/)


## 📌 Features

- 🎯 Two-player turn-based gameplay
- 🎲 Random dice rolling using JavaScript
- 💡 Intuitive UI with active player indication
- 💾 Game state logic including current score and total score tracking
- 🔁 "Hold" and "New Game" functionality
- 📱 Responsive design for desktop and mobile


## 🛠️ Technologies Used

- **HTML5** - Markup structure
- **CSS3** - Styling and layout
- **JavaScript (Vanilla)** - Game logic and interactivity


## 🚀 Getting Started

To run the game locally:

1. Clone this repository:  

   ```bash
   git clone https://github.com/RuhulAminSharif/Pig-Game.git
   ```
  
2. Navigate to the project directory:

   ```bash
   cd Pig-Game
   ```
3. Open the `index.html` file in your browser:

   ```bash
   open index.html
   ```

Alternatively, just visit the [Live Demo](https://ruhulaminsharif.github.io/Pig-Game/)!


## 📋 Rules

1. Each player takes turns rolling a dice.
2. On each roll:

   * If the dice shows **1**, the current turn score resets to 0 and the turn passes to the next player.
   * Otherwise, the rolled value is added to the current score.
3. A player can choose to **"Hold"**:

   * The current score is added to their total score.
   * The turn passes to the other player.
4. The first player to reach **100** total points wins the game.


## 👨‍💻 Author

**Ruhul Amin Sharif**
🔗 [GitHub](https://github.com/RuhulAminSharif)


## 🙌 Acknowledgements

* Inspired by Jonas Schmedtmann's JavaScript projects.
* Dice icon & assets from [FontAwesome](https://fontawesome.com/)

