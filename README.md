# River Cross 1v1 Game

River Cross 1v1 Game is a Python game developed using the Pygame library. It simulates a scenario where players navigate a character across a river filled with obstacles while avoiding hazards and collecting points.

## Features

- **Multiplayer Support**: The game supports multiplayer functionality, allowing two players to compete against each other.
- **Character Control**: Players control their characters using keyboard inputs to move left, right, up, or down.
- **Health and Points System**: Each player has a health meter that decreases upon colliding with obstacles. Points are awarded based on performance.
- **Timer**: A timer tracks the elapsed time during gameplay.
- **Dynamic Obstacles**: The game features dynamically moving obstacles such as boats and fire blocks that pose challenges to the players.
- **Game End Handling**: The game handles end conditions such as running out of health or time, displaying results, and allowing players to restart or quit.
- **Animated Character Movements**: The character's movements are animated, providing visual feedback to the players.
- **Responsive User Interface**: The game window provides a responsive user interface, rendering game elements and descriptors effectively.

## How to Play

1. **Controls**:
   - Use the arrow keys (UP, DOWN, LEFT, RIGHT) to navigate your character across the river.
   - Press 'R' to play again, 'Q' to quit, and 'N' to proceed to the next player (in multiplayer mode).

2. **Objective**:
   - Navigate your character across the river while avoiding collisions with obstacles.
   - Collect points by reaching the end of the river within the time limit.

3. **Gameplay**:
   - Avoid collisions with moving boats and fire blocks.
   - Manage your character's health to prevent it from reaching zero.
   - Reach the end of the river within the time limit to win the game.

4. **Multiplayer Mode**:
   - Compete against another player in a 1v1 river crossing challenge.
   - The player with the highest score wins the game.

## Requirements

To run the game, ensure you have the following installed:

- Python (3.x recommended)
- Pygame library

## Getting Started

1. Clone the repository to your local machine.
2. Install the Pygame library using pip:

   ```
   pip install pygame
   ```

3. Run the game by executing the main Python script:

   ```
   python main.py
   ```
