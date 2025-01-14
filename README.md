# Archery

This is a browser-based arrow shooting game that involves shooting arrows at a moving board to score points. The game features interactive animations, sound effects, and scoring mechanics.The game starts with an easy gameplay but as the player moves forward the difficulty increases. I have worked on the functionality more than the design.
---
## Features

- **Dynamic Gameplay**: A moving board and dynamic difficulty progression.
- **Audio Effects**: Includes various sound effects for shooting, hitting the target, scoring, and more.
- **Responsive Design**: Adapts to both portrait and landscape orientations.
- **Interactive UI**: Players can interact using mouse clicks or keyboard inputs.
---
## How to Play

1. **Start the Game**:
   - Click on the start menu to begin the game.
   - The start menu will disappear, and the game will load.

2. **Objective**:
   - Shoot arrows at the moving board.
   - Aim to hit the board as close to the center as possible to score higher points.

3. **THe Board**:
   - After a few hits the board also starts to move vertically just as the bow does to make it difficult for the player to aim.

4. **Controls**:
   - **Mouse Click**: Click on the canvas to shoot an arrow.
   - **Keyboard**: Press any key to shoot an arrow.

5. **Scoring**:
   - Hitting closer to the center of the board gives higher scores.
   - Special effects and bonuses are triggered for high scores.
   - When you hit the center you score 8 points and then as you hit the board away from the center, the points keep decreasing.

6. **Game Over**:
   - The game ends when you run out of arrows.
---
### Key Components

1. **Audio Management**:
   - Manages the playback of sound effects for actions like shooting, hitting, and success.

2. **Canvas Drawing**:
   - Uses the HTML5 Canvas API to draw and animate game elements like the board, arrows, and fireworks.

3. **Event Listeners**:
   - Handles mouse clicks and keyboard inputs to shoot arrows.

4. **Dynamic UI Updates**:
   - Updates the score display and other UI elements dynamically based on game actions
---
### Main Files

- **index.html**: The main HTML file that hosts the game.
- **style.css**: For styling the game UI.
- **script.js**: Contains the main game logic (the provided JavaScript code).
---
### Functions and Logic

- **startGame**: Initializes the game when the start button is clicked.
- **shoot**: Handles the shooting logic, including arrow movement and scoring.
- **loadGame**: Sets up the game canvas, elements, and animations.
- **animateScore**: Animates the score display after each hit.
---
