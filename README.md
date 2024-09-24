# Task-2: Number Guessing Game

This Java program implements a simple number guessing game where the player must guess a randomly generated number within a specified range. The game consists of multiple rounds, with a limited number of attempts to guess the correct number in each round.

## How to Play

### Setup
- The game generates a random number within a specified range (default: 1 to 100).
- You have a limited number of attempts to guess the correct number (default: 10 attempts per round).
- The game consists of a total of 3 rounds.

### Playing a Round
1. In each round, you will be prompted to guess the number within the given range.
2. Enter your guess and receive feedback on whether the actual number is greater or smaller than your guess.
3. Try to guess the number within the allotted attempts for each round.

### Scoring
- Points are earned based on the number of attempts left after correctly guessing the number.
- The score for each round is calculated as: 

### Total Score
- Your total score is the sum of scores from all rounds played.

## Game Over
- After completing the specified number of rounds, the game ends, and your total score is displayed.

## Customize the Game
You can customize the game by adjusting the following constants in the `Task2` class:
- `MIN_RANGE`: Minimum value for the random number generation.
- `MAX_RANGE`: Maximum value for the random number generation.
- `MAX_ATTEMPTS`: Maximum attempts allowed to guess the number in each round.
- `MAX_ROUNDS`: Total number of rounds in the game.

## Running the Program
1. Compile the Java file (`Task2.java`).
2. Run the compiled Java program.

## Contributing
Feel free to contribute to this project by creating issues, suggesting improvements, or submitting pull requests. Your contributions are welcome and appreciated!

