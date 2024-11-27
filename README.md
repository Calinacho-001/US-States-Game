# U.S. States Guessing Game 

## Description

The U.S. States Guessing Game is an interactive Python game where players are challenged to guess the names of all 50 U.S. states. A map of the U.S. is displayed, and players can type the names of states to see if they are correct. As states are guessed correctly, their names appear on the map. The game tracks how many states the player has correctly guessed out of 50.

This project demonstrates the use of **Python's turtle graphics module** for displaying the map and **pandas** for handling state data and storing progress.

## Features

- **Interactive Gameplay**: Type the name of a state to guess if it's correct.
- **Map of the U.S.**: States are displayed on a U.S. map as they are guessed correctly.
- **Exit Option**: Type "Exit" to end the game and save the list of unguessed states for later review.
- **Tracking Progress**: The game keeps track of how many states have been guessed correctly.

## Requirements

- Python 3.x
- `turtle` graphics module (pre-installed with Python)
- `pandas` library (install via `pip install pandas`)

## How to Play

1. **Start the Game**:
   - Run the `game.py` script to start the game.

2. **Guess the States**:
   - Type the name of a U.S. state when prompted.
   - If the guess is correct, the state name will appear on the map.

3. **Exit the Game**:
   - Type "Exit" to end the game early. A CSV file with the states you haven't guessed will be saved for future reference.

4. **Goal**:
   - The goal is to guess all 50 states. The game ends when all states have been guessed or when the player exits.

## Code Structure

### Files Breakdown

Here is a breakdown of each file and its purpose in the game:

---

### `game.py`

- **Purpose**: This is the main game script that runs the U.S. States Guessing Game. It sets up the game window using turtle graphics, handles user input for guessing states, and displays the state names on a map.
- **Key Functionality**:
  - Displays the U.S. map and prompts the player to guess states.
  - Tracks the guessed states and updates the map with each correct guess.
  - Saves unguessed states to a CSV file when the game is exited.

---

### `50_states.csv`

- **Purpose**: This file contains the coordinates (`x` and `y` values) for each U.S. state on the map, which are used to position the state names on the map when guessed correctly.
- **Key Columns**:
  - `state`: The name of the state.
  - `x`: The x-coordinate of the state on the map.
  - `y`: The y-coordinate of the state on the map.

---

### `blank_states_img.gif`

- **Purpose**: A GIF image of the blank U.S. map that is used as the background for the game.
- **Key Functionality**: The map is displayed as the backdrop for the game where the guessed states will appear.

---

## How to Run

1. Clone or download the project files.
2. Ensure Python 3.x is installed on your computer.
3. Install the `pandas` library if you haven't already:

```bash
pip install pandas
```

4. Open a terminal or command prompt and navigate to the project directory.
5. Run the following command to start the game:

```bash
python game.py
```

6. The game will prompt you to guess U.S. states. Type the names of the states when prompted, and they will appear on the map once correctly guessed.

## Future Improvements

- **Visual Enhancements**: Add color or animations when a state is guessed correctly.
- **Timer**: Add a timer to track how long it takes the player to guess all the states.
- **Leaderboard**: Track and display the best times or scores for the game.
- **Multiple Difficulty Levels**: Offer different levels of difficulty, such as showing state names or abbreviations.

## Credits

This project was created to demonstrate the use of Python's **turtle graphics** and **pandas** for data manipulation. The map image and CSV data were sourced from open educational resources.




