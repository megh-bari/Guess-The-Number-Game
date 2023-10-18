# Guess the Number Game

This is a simple command-line based "Guess the Number" game in C. The game generates a random number between 1 and 100, and the player's objective is to guess the correct number. The program will provide hints for guessing higher or lower until the correct number is guessed.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [License](#license)

## Features

- Random number generation between 1 and 100.
- Interactive gameplay with hints for the player.
- Keeps track of the number of attempts.

## Getting Started

To get started with the game on your local machine, follow these steps:

1. **Clone the repository:**
```bash
   git clone https://github.com/yourusername/guess-the-number-game.git
 ```
 2. **Compile the code:**
```bash
 gcc guess_the_number.c -o guess_the_number
```  
  
3.**Run the game:**
```bash
./guess_the_number
``` 
## How to Play
- The game will generate a random number between 1 and 100.
- You need to guess the number by entering an integer between 1 and 100.
- The game will provide hints:
  - If your guess is higher than the target number, it will say "Lower number please!"
  - If your guess is lower than the target number, it will say "Higher number please!"
  - If your guess is correct, it will tell you how many attempts you took to guess the number.
 
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, or suggest improvements. Enjoy the game!


