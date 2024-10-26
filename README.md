# AI-Based Tic Tac Toe Player

This is an AI-based Tic Tac Toe player developed in Java, designed to offer an interactive and flexible gaming experience. Players can either play against each other (Player vs. Player) or play against the computer, where the AI uses a simple search tree to make decisions. In computer mode, users can select different search strategies (BFS or DFS), difficulty levels, and grid sizes to customize their gameplay.

## Features

- **Modes**: 
  - **Player vs. Player (PvP)**: Two human players can compete on the same grid.
  - **Player vs. Computer**: Play against the AI with varying difficulty.
  
- **AI Strategies**:
  - **Breadth-First Search (BFS)**: AI evaluates possible moves using a BFS algorithm.
  - **Depth-First Search (DFS)**: AI evaluates possible moves using a DFS algorithm.
  
- **Configurable Difficulty**: Adjust the AI's difficulty level for an easier or harder game.
  
- **Variable Grid Sizes**: Play on grids larger or smaller than the standard 3x3.

## Quick Start

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Simba256/AI-TicTacToe-Java.git
   cd AI-TicTacToe

2. **Configure the Game Mode**:
   Open `TicTacToe.java`, find the line with `HUMAN_VS_COMPUTER` in the class and set it to `true` to play against the computer or `false` for Player vs. Player mode.
   ```java
   protected final boolean HUMAN_VS_COMPUTER = true; // Set to false for PvP mode
   ```

3. **Run the Game**:
   Compile and run the main file, `AssigThree224.java`, to start the game.
   ```bash
   javac AssigThree224.java
   java AssigThree224
   ```

## Game Configuration

### Switching Between Modes
In `TicTacToe.java`, toggle the `HUMAN_VS_COMPUTER` variable to `true` or `false` depending on whether you want to play Player vs. Computer or Player vs. Player mode:
```java
protected final boolean HUMAN_VS_COMPUTER = true; // Is the user playing against the computer?
```

### Choosing AI Strategy
If playing against the computer, you can select the AI strategy (BFS or DFS) in the settings. Adjustments to the search strategy, difficulty, or grid size may be available directly in the code (check relevant class variables and method comments).

## File Structure

- **AssigThree224.java** - The main entry point for running the game.
- **TicTacToe.java** - Contains the core logic of the Tic Tac Toe game, including player modes and settings.
- **AI.java** - Implements the AI strategies (BFS and DFS) for gameplay.
- **README.md** - Documentation for setting up and running the project.

## Requirements

- **Java 8+** - Ensure you have Java installed to compile and run the game.

## Contributing

Feel free to fork this project, submit issues, or make pull requests to improve the game. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Enjoy playing Tic Tac Toe with customizable AI on your preferred grid size and strategy!
