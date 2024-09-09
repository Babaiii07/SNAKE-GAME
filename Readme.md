```markdown
# Snake Game

This project is a simple Snake game built using Python's `pygame` library. The goal of the game is to control a snake, collect food, and grow the snake while avoiding the boundaries of the game screen.

## Features
- Snake Movement: Use the arrow keys to control the snake's movement (up, down, left, right).
- Food Collection: As the snake collects food, it grows longer, and the player's score increases.
- Game Over Condition: The game ends when the snake hits the boundaries of the game window.
- Score Display: The player's score is displayed on the screen.
- Restart Option: Players can press 'P' to play again after losing, or 'Q' to quit.

## Requirements
- Python 3.x
- `pygame` library

## Installation
1. Install Python from [python.org](https://www.python.org/downloads/).
2. Install the `pygame` library:
   ```bash
   pip install pygame
   ```

## How to Play
1. Run the game:
   ```bash
   python snake_game.py
   ```
2. Control the snake using the arrow keys:
   - Left Arrow: Move left
   - Right Arrow: Move right
   - Up Arrow: Move up
   - Down Arrow: Move down
3. Collect the red food blocks to grow your snake and increase your score.
4. Avoid running into the edges of the screen, or the game will be over.
5. If you lose, press:
   - P to play again.
   - Q to quit the game.

## Game Settings
- Display Size: The game window is set to 600x400 pixels.
- Snake Speed: The snake moves at 15 blocks per second.
- Snake Block Size: The snake and food blocks are 10x10 pixels.
- Colors:
   - Background: Black
   - Snake: Green
   - Food: Red
   - Score: Yellow
   - Message: Red

## License
This project is open-source and can be modified or redistributed.
```

This `README.md` provides a concise overview of the Snake game and includes instructions for setting up and playing the game.