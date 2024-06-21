# Snake Game

This repository contains a simple Snake game implemented in Java using Swing. The game provides a classic Snake gameplay experience where the player controls a snake to eat apples and grow in size, while avoiding collisions with the walls or its own body.

## Features

- Classic Snake gameplay
- Responsive controls using arrow keys
- Score display
- Game Over screen

## Installation

1. **Run snake.exe:**
    ```
   double click snake.exe
   ```
    
### ------------------ OR -----------------

1. **Clone the repository:**
    ```bash
    git clone git@github.com:rukshan-forg/Snake_GAME.git
    cd snake-game
    ```

2. **Compile the game:**
    ```bash
    javac GameFrame.java
    ```

3. **Run the game:**
    ```bash
    java SnakeGame
    ```

## How to Play

- Use the following keys to control the snake:
  - `W`: Move up
  - `S`: Move down
  - `A`: Move left
  - `D`: Move right
- Eat the red apples to grow the snake's length and increase your score.
- Avoid running into the walls or the snake's own body.

## Code Structure

- **SnakeGame.java:** The main class that starts the game by creating an instance of `GameFrame`.
- **GameFrame.java:** Sets up the game window and adds an instance of `GamePanel`.
- **GamePanel.java:** Handles the game logic, drawing, and user input.

## Key Classes and Methods

### `GamePanel.java`

- **Constructor:** Initializes the game panel, sets up the game dimensions, and starts the game.
- **startGame():** Starts the game by creating a new apple, setting the game running state to true, and starting the timer.
- **paintComponent(Graphics g):** Draws the game components on the panel.
- **draw(Graphics g):** Draws the grid, apple, snake, and score.
- **newApple():** Places a new apple at a random location on the screen.
- **move():** Moves the snake in the current direction.
- **checkApple():** Checks if the snake has eaten the apple and increases the snake's size and score.
- **checkCollisions():** Checks for collisions with the walls or the snake's body.
- **gameOver(Graphics g):** Displays the Game Over screen with the final score.
- **actionPerformed(ActionEvent e):** Called by the timer to update the game state and repaint the panel.
- **MyKeyAdapter:** Handles user input to change the direction of the snake.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements

This game is inspired by the classic Snake game that has been a part of gaming history for decades. Special thanks to all the developers who have kept this game alive over the years.


