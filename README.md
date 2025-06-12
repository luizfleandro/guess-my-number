# Number Guessing Game

A simple interactive game where the player tries to guess a randomly generated number between 1 and 20. The system provides hints after each guess to guide the player toward the correct number.

## Gameplay

- When the game starts, the system secretly picks a number between **1 and 20**.
- The player enters a guess.
- After each guess, the system gives a hint:
  - "Too high!" if the guess is greater than the number.
  - "Too low!" if the guess is less than the number.
  - "Correct!" if the guess is right.

The goal is to guess the correct number in as few attempts as possible.

## Features

- Random number generation between 1–20
- Instant feedback on each guess
- Simple and intuitive interface (CLI or GUI, depending on your implementation)
- Replayable

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/number-guessing-game.git
cd number-guessing-game
