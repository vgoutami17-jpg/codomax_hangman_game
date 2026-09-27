# Codomax - Hangman Game

## Project Overview

This project is a simple text-based Hangman Game developed using Python as part of the Codomax Python Programming Internship.

In this game, the computer randomly selects a word from a list of predefined words. The player has to guess the word by entering one letter at a time.

The player is allowed a maximum of 6 incorrect guesses.

## Objective

The objective of this project is to create a simple console-based Hangman game using basic Python programming concepts.

## Features

- Randomly selects a word from 5 predefined words
- Allows the player to guess one letter at a time
- Allows a maximum of 6 incorrect guesses
- Prevents repeated letter guesses
- Displays the progress of the hidden word
- Displays a winning message when the word is completely guessed
- Displays a game-over message when the player reaches 6 incorrect guesses
- Runs completely in the console

## Predefined Words

The game uses the following 5 predefined words:

1. Python
2. Computer
3. Programming
4. Keyboard
5. Internet

## Technologies Used

- Python
- Google Colab
- GitHub

## Python Concepts Used

- Random module
- Lists
- Strings
- While loop
- For loop
- If-else statements
- User input

## How the Game Works

1. The program starts the Hangman game.
2. A word is randomly selected from the predefined word list.
3. The selected word is hidden using underscores.
4. The player enters one letter at a time.
5. If the letter is correct, it is displayed in its correct position.
6. If the letter is incorrect, the incorrect guess count increases.
7. The player can make a maximum of 6 incorrect guesses.
8. The game ends when the player guesses the word or reaches 6 incorrect guesses.

## How to Run

1. Open the `Codomax_HangmanGame.ipynb` file.
2. Open the notebook in Google Colab.
3. Run the Python cells.
4. Enter one letter at a time when prompted.
5. Continue guessing until you win or reach 6 incorrect guesses.

## Project Files

| File | Description |
|------|-------------|
| `Codomax_HangmanGame.ipynb` | Python source code for the Hangman game |
| `README.md` | Project documentation |

## Sample Output

```text
Welcome to Hangman!
Guess the word one letter at a time.

Word: _ _ _ _ _ _
Incorrect guesses: 0 / 6

Guess a letter: p
Correct guess!

Word: p _ _ _ _ _
Incorrect guesses: 0 / 6

Guess a letter: x
Incorrect guess!

Word: p _ _ _ _ _
Incorrect guesses: 1 / 6
