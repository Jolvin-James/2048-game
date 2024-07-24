## 2048 Game in Python

This is an implementation of the popular 2048 game using Python and the Tkinter library for creating the graphical user interface (GUI).

### Features

- **4x4 grid** to play the game
- **Random cell generation** at the start of the game
- **Smooth animation** when tiles move or merge
- **Score tracking**
- **Game over** detection when no more moves are possible
- **Win detection** when a tile with value 2048 is created

### How to Play

Use the arrow keys (Up, Down, Left, Right) to move the tiles. Tiles with the same number merge into one when they collide. The goal is to create a tile with the value 2048.

### Code Structure

The code defines two classes:

1. **Board**: This class represents the game board and handles the logic of moving tiles, merging tiles, and updating the GUI.

2. **Game**: This class manages the game state, handles user input, and coordinates the game logic with the Board class.

The main flow of the game is as follows:

1. The `Board` class is initialized, creating the game window and setting up the initial grid.
2. The `Game` class is initialized with the `Board` instance and starts the game loop.
3. Two random cells are placed on the board at the start of the game.
4. The game window is displayed, and the user can start playing by pressing the arrow keys.
5. When an arrow key is pressed, the corresponding move is executed, and the game state is updated accordingly.
6. If a tile with value 2048 is created, a "You Won!" message is displayed, and the game ends.
7. If no more moves are possible and no tile with value 2048 exists, a "Game Over!" message is displayed, and the game ends.
8. If a move is made, a new random cell is placed on the board.
9. The game board is redrawn to reflect the updated state.

### Dependencies

- Python 3.x
- Tkinter library (comes pre-installed with Python)

### How to Run

1. Save the code in a file with a `.py` extension (e.g., `2048.py`).
2. Open a terminal or command prompt and navigate to the directory containing the saved file.
3. Run the following command:

```bash
python 2048.py
```

4. The 2048 game window will appear, and you can start playing by using the arrow keys.

Enjoy playing 2048!

Citations:
[1] https://projectgurukul.org/python-2048-game/
[2] https://stackoverflow.com/questions/66991017/why-does-from-tkinter-import-not-import-tkinters-messagebox
[3] https://github.com/basler/pypylon/issues/72
[4] https://forums.raspberrypi.com/viewtopic.php?t=217200
[5] https://wenku.csdn.net/answer/f60088227f6748cf80c62ffbb91bc1ec
