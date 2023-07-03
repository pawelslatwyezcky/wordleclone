# Wordle Clone

![Wordle Interface](https://github.com/pawelslatwyezcky/wordleclone/blob/main/WORDLE.png?raw=true)

This repository contains a Wordle clone, a JavaScript project that aims to recreate the popular game Wordle. Wordle is a word-guessing game where players try to guess a hidden five-letter word by making guesses and receiving feedback on the correctness of their guesses.

## Demo

A live demo of the Wordle Clone can be found [here](https://pawelslatwyezcky.github.io/wordleclone/).

## Getting Started

To get started with the Wordle Clone, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/pawelslatwyezcky/wordleclone.git`.
2. Open the project in your preferred code editor.
3. Open the `index.html` file in a web browser to play the game.

## How to Play

- The game will randomly select a five-letter word for you to guess.
- Make a guess by typing a five-letter word in the input field and clicking the "Guess" button.
- After each guess, you will receive feedback on the correctness of your guess.
- A correct letter in the correct position will be marked with a green dot (`.`).
- A correct letter in the wrong position will be marked with a yellow dot (`.`).
- An incorrect letter will not be marked.
- Keep making guesses until you correctly guess the word or run out of attempts.

## Project Structure

The project structure is as follows:

```
.
├── index.html
├── css
│   └── styles.css
├── js
│   └── main.js
└── wordlist
    └── words.txt
```

- `index.html`: The HTML file that displays the game interface.
- `css/styles.css`: The CSS file for styling the game.
- `js/main.js`: Contains the main game logic and handles user input.
- `wordlist/words.txt`: A text file containing a list of words used for guessing.

## Technologies Used

- HTML
- CSS
- JavaScript

## Contributing

Contributions to this project are welcome! If you have any suggestions, improvements, or find any issues, please feel free to submit a pull request.

## Acknowledgements

This Wordle Clone project was inspired by the original Wordle game created by Joshua Wardle.
