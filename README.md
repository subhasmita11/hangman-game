The Hangman game is a classic word-guessing game where the player tries to guess a hidden word by suggesting letters. In this C++ implementation, players interact with the game through the console, attempting to discover the secret word within a limited number of incorrect guesses.
# Hangman Game in C++

## Introduction

This is a simple console-based Hangman game implemented in C++. The game allows players to guess a word by entering letters, with a limited number of incorrect guesses allowed before the game ends.
Features
Randomly selects a word from a predefined list.
Allows players to guess letters.
Tracks incorrect guesses and updates the hangman figure.
Ends the game when the player correctly guesses the word or exceeds the maximum allowed incorrect guesses.
# Clone the repository to your local machine.

git clone https://github.com/subhasmita11/hangman-game.git

# Code Structure
The main code file is hangman_functions.cpp. The program is organized into functions for better readability and maintainability.

generateRandomWord(): Selects a random word from a predefined list.
displayWord(): Displays the current state of the word with correctly guessed letters and underscores for unknown letters.
guessLetter(): Handles the player's letter input and updates the game state accordingly.
drawHangman(): Draws the hangman figure based on the number of incorrect guesses.
isGameOver(): Checks if the game is over (either the word is guessed or too many incorrect guesses).


# Contributing
Feel free to contribute to the project by submitting issues or pull requests. Bug fixes, new features, and improvements are welcome.

# License
This Hangman game is licensed under the MIT License. See the LICENSE file for details.
This README provides basic information about the game, instructions on how to play, details on the code structure, and guidance for contributing and licensing. Customize it as needed based on the specific details of your Hangman game implementation.


