# Turtle Crossing Game

This is an entertaining game built with Python's Turtle graphics library. The player controls a turtle that must cross a busy road while avoiding cars. As the player progresses, the game becomes increasingly challenging with faster traffic.

## Features

- Player-controlled turtle character
- Randomly generated cars with varying colors
- Increasing difficulty as the player advances
- Score tracking system
- Game over screen

## Files

- `main.py`: The main game script that ties everything together
- `player.py`: Contains the Player class, managing the turtle's behavior
- `car_manager.py`: Handles the creation and movement of cars
- `scoreboard.py`: Manages the game's scoring system and level display

## Requirements

- Python 3.x
- Turtle graphics library (usually comes pre-installed with Python)

## How to Run

1. Ensure you have Python installed on your system.
2. Place all the Python files (`main.py`, `player.py`, `car_manager.py`, and `scoreboard.py`) in the same directory.
3. Run the game by executing the `main.py` file:
   ```
   python main.py
   ```

## How to Play

1. Use the "Up" arrow key to move the turtle forward.
2. Use the "Down" arrow key to move the turtle backward.
3. Try to cross the road without getting hit by any cars.
4. Each successful crossing increases your level, and the game gets faster.
5. The game ends if the turtle collides with a car.

## Game Mechanics

- The player starts at the bottom of the screen.
- Cars move from right to left at varying speeds.
- The player must guide the turtle to the top of the screen without colliding with any cars.
- Upon reaching the top, the player's level increases, and they start again from the bottom.
- The car speed increases with each level, making the game progressively harder.
- The game continues until the turtle collides with a car.

## Customization

You can customize the game by modifying the following:

- In `car_manager.py`:
  - Adjust `COLORS` to change car colors
  - Modify `STARTING_MOVE_DISTANCE` and `MOVE_INCREMENT` to alter game difficulty
- In `player.py`:
  - Change `STARTING_POSITION`, `MOVE_DISTANCE`, or `FINISH_LINE_Y` to alter game dynamics
- In `scoreboard.py`:
  - Modify `FONT` to change the game's text appearance

## Contributing

Feel free to fork this project and make your own modifications. Some ideas for enhancements:
- Add sound effects
- Implement different levels with unique obstacles
- Create a high score system
- Add power-ups or bonuses
- Implement multiple lives for the player
- Create a graphical menu system

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
