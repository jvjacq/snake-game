# Snake Game in Python

A classic game implemented using Python and the Pygame library.

## Features

- **Classic Gameplay**: Navigate the snake to eat food and grow longer.
- **Dynamic Scoring**: Keep track of your score as you collect food.
- **Simple Controls**: Use the arrow keys to control the snake's movement.
- **Game Over Screen**: View your final score and options to restart or quit.

## Gameplay

1. **Objective**: Guide the snake to eat the red food blocks. Each food eaten increases your score and the length of the snake.
2. **Controls**:
   - **Up Arrow**: Move Up
   - **Down Arrow**: Move Down
   - **Left Arrow**: Move Left
   - **Right Arrow**: Move Right
3. **End Condition**: The game ends when the snake collides with the walls or itself. After a game over, you can choose to restart or exit.

## Code Overview

The project consists of a single Python file that utilizes:
- **Pygame**: For graphics and game mechanics.
- **Enum**: To manage directions.
- **Namedtuples**: For easy representation of points on the screen.

### Key Classes and Methods

- **SnakeGame**: The main class that handles game initialization, gameplay logic, and rendering.
  - **play_step()**: Processes user input, updates the snake's position, checks for collisions, and updates the score.
  - **_place_food()**: Randomly places food on the board.
  - **_is_collision()**: Checks for collisions with walls or the snake's body.
  - **game_over_screen()**: Displays the game over screen with the final score.

## Visuals

The game features a simple graphical interface with:
- A black background.
- Green blocks representing the snake.
- Red blocks representing the food.

## Screenshots

Here are some screenshots of the game in action:

