# Number-Guessing-Game
Welcome to the **Number Guessing Game** repo! This is a simple game where the player tries to guess a randomly generated number between 1 and 100. You have a limited number of attempts based on the difficulty level you choose.

## Features

- **Random Number Generation**: The program generates a random number between 1 and 100.
- **Difficulty Levels**:
  - **Easy**: 10 attempts to guess the correct number.
  - **Hard**: 5 attempts to guess the correct number.
- **Feedback**: After each guess, the game will tell you if your guess is too high or too low.
- **Replayable**: The game can be played multiple times in a single session.

## Functions
* **check_answer(user_guess, actual_answer, turns):** Checks whether the guess is too high, too low, or correct. Reduces the number of remaining turns for incorrect guesses.
* **set_difficulty():** Allows the user to choose between two difficulty levels: 'easy' (10 turns) or 'hard' (5 turns).
* **game():** Runs the main game loop, generating the random number and processing user inputs.

