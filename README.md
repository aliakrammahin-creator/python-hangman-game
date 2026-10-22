# Python Hangman Game

## About the Project

This is a Hangman game I built while learning Python through Angela Yu's 100 Days of Code: The Complete Python Pro Bootcamp.

The computer randomly selects a word, and the player has to guess it one letter at a time. The goal is to find the complete word before running out of lives.

## How to Play

1. Run `main.py` to start the game.
2. The computer selects a random word and displays blanks for each letter.
3. Enter a letter to guess the word.
4. Correct guesses reveal the matching letters.
5. Incorrect guesses reduce your remaining lives.
6. The game ends when you guess the word correctly or run out of lives.

## Features

- Random word selection
- Tracks correctly guessed letters
- Displays the remaining lives
- ASCII art for the game logo and hangman stages
- Win and lose messages

## Project Structure

- `main.py` — Contains the main game logic.
- `hangman_words.py` — Contains the list of words used in the game.
- `hangman_art.py` — Contains the game logo and hangman stages.

## Requirements

- Python 3
- No external libraries required

## How to Run

1. Download or clone this repository.
2. Make sure Python 3 is installed on your computer.
3. Open a terminal in the project folder.
4. Run the following command:

   `python main.py`

   If that command doesn't work on Windows, try `py main.py`.

## What I Learned

While building this project, I practised:

- Using `while` and `for` loops
- Working with lists and strings
- Using conditional statements
- Importing variables from other Python files
- Generating random selections with the `random` module
- Managing game states and tracking the player's remaining lives

This project helped me practise the fundamentals of Python by applying them to a simple interactive game.
