# Snake-Game
Snake Game is built using Tkinter in Python. Game features a snake that moves around the screen, consuming food to grow longer. The player controls the snake's direction using arrow keys. The objective is avoid hitting walls or the snake’s own body. Each food item eaten increases the score.

This Snake Game is a simple implementation of the classic arcade game using Python's Tkinter library for the graphical interface. The game window has a grid where the snake and food interact. The snake moves continuously in the selected direction (up, down, left, right), and each time it consumes food, it grows longer. The player's goal is to avoid collisions with the screen's borders or the snake's own body, which would result in a game-over.

Key features:

Game Mechanics: The snake moves in discrete spaces, and its body is represented as a series of squares. The game operates on a grid where each square is 25 pixels. The snake is controlled using the arrow keys.
Food: Food appears randomly on the grid. When the snake eats the food, it grows by one body part, and the score increases. A new piece of food is generated after each consumption.
Collisions: The game checks for collisions with the edges of the screen or with the snake’s own body. If a collision occurs, the game ends, and the player is shown a game-over screen with their final score.
UI Elements: A label displays the current score, which is updated each time the snake eats food. The game over message is displayed in the center of the screen when the game ends.
Game Speed: The game runs with a speed set by the speed variable, which determines how fast the snake moves. This can be adjusted to increase or decrease the difficulty.
The game logic is organized into classes (Snake and Food) to manage the snake’s body parts and food generation. The collision detection ensures the game ends if the snake crashes into the walls or itself.

Overall, this is a simple, yet engaging Python game, suitable for learning basic game mechanics and working with the Tkinter GUI framework.








