# Snake-Game
This Snake game is a simple implementation using Java and the Swing library for graphical user interface components. The game consists of a snake controlled by the player to navigate and consume apples, earning points for each apple eaten.

The main components of the game include:

1) GameFrame Class:
- This class extends JFrame and serves as the main window for the game.
- It initializes a GamePanel and sets up various properties for the frame, such as title, close operation, resizable, packing, visibility, and location.
  
2) GamePanel Class:
- Extending JPanel, this class handles the game's logic and rendering.
- It defines constants for screen dimensions, unit size, game units, delay, and arrays for the snake's coordinates.
- The game includes a timer for periodic updates, random apple placement, and a restart button upon game over.
- Snake movement is determined by arrow key input from the player.
- Collision detection ensures that the snake interacts correctly with the borders, itself, and the apples.
- The game keeps track of the player's score, and a game-over screen is displayed with the final score and an option to restart.
  
3) MyKeyAdapter Class:
- This internal class extends KeyAdapter and handles keyboard input for changing the snake's direction.

4) SnakeGame Class:
- The main class that contains the main method to start the game. It creates an instance of GameFrame to initiate the game.

The game offers a classic Snake experience, where the player maneuvers the snake to eat apples, grows longer with each apple consumed, and ends when the snake collides with the screen borders or itself. The restart button provides a way for players to replay the game after a game-over scenario. The graphical interface is implemented using Java's Swing library, offering a visually appealing and interactive gaming experience.



https://github.com/NaumanSayed/Snake-Game/assets/141490106/33ce5a6f-2503-494c-912a-050ba7361376






