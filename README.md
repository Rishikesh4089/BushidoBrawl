
---

# Samurai Showdown

A dynamic 2D fighting game where two samurai warriors battle it out in an exciting combat arena. This game features intuitive controls for movement, jumping, and slashing. The goal is simple: deplete your opponent's health to win the match.

## Game Features

- **Two Fighters:** Play as either Player 1 or Player 2, each with unique animations for idle, running, jumping, falling, attacking, taking hits, and death.
- **Movement Controls:** 
  - **Player 1**: Move left with 'A', right with 'D', jump with 'W', and attack with 'Space'.
  - **Player 2**: Move left with the Left Arrow, right with the Right Arrow, jump with the Up Arrow, and attack with the Down Arrow.
- **Health Bars:** Both players have a health bar displayed at the top. The match ends when one player's health reaches zero.
- **Collision Detection:** The game uses rectangle collision detection to determine when an attack hits the opponent, leading to a health decrease.
- **Background Animation:** A custom background and shop are present in the game environment.
- **Responsive Layout:** The game scales based on the window size, adjusting the background and other components accordingly.

## Setup Instructions

### Prerequisites

Make sure you have the following installed:
- A modern web browser (Chrome, Firefox, Safari, etc.)

### Installation

1. Clone the repository or download the project files to your local machine.
2. Open the `index.html` file in your browser to start the game.
3. (Optional: If you just want to try out the game) Open the production link from my Github repository.

### Directory Structure

```
/img
  ├── background.png
  ├── shop.png
  ├── samuraiMack
  │    ├── Idle.png
  │    ├── Run.png
  │    ├── Jump.png
  │    └── ... (other animations)
  └── kenji
       ├── Idle.png
       ├── Run.png
       ├── Jump.png
       └── ... (other animations)
index.html
main.js
README.md
```

### Controls

- **Player 1 (Left Samurai):**
  - **Move Left:** Press 'A'
  - **Move Right:** Press 'D'
  - **Jump:** Press 'W'
  - **Attack:** Press 'Space'

- **Player 2 (Right Samurai):**
  - **Move Left:** Press Left Arrow
  - **Move Right:** Press Right Arrow
  - **Jump:** Press Up Arrow
  - **Attack:** Press Down Arrow

### Game Objective

The objective of the game is to defeat your opponent by depleting their health bar. You can perform different movements and attacks to deal damage, with animations triggered based on actions like running, jumping, or slashing.

### How to Play

- Use the movement keys to position your character.
- Jump to avoid attacks or to gain better positioning.
- Press the attack key when close to your opponent to land a hit.
- Be mindful of your health, and make sure to attack at the right time while avoiding enemy attacks.

## Game Development

This project was developed using **HTML5**, **JavaScript**, and **CSS** for styling. It includes canvas rendering for smooth animations and interactions.

### Technologies Used:
- **HTML5 Canvas API** for rendering animations and game logic.
- **JavaScript** for game mechanics, character movement, and collision detection.
- **Sprites & Animation**: Character sprites and other game assets are loaded to create the animations.

## Contributing

Feel free to fork the repository and make contributions! If you have any suggestions or find bugs, open an issue, and I'll be happy to work on improvements.

## License

This project is open-source and available under the MIT License.

---
