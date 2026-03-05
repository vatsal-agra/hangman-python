# Hangman

A classic Hangman game with a twist — built using Python's Turtle graphics for the drawing and Tkinter for the UI. One player secretly enters a word, the other guesses letters one at a time, with a limited hint system and a progressively drawn hangman figure tracking wrong guesses.

## How It Works

1. Player 1 enters a secret word (hidden behind `?` characters as they type)
2. A Turtle window opens showing blank dashes for each letter
3. Player 2 guesses one letter at a time
4. Correct guesses reveal the letter's position on the dashes
5. Wrong guesses draw the hangman figure step by step (6 lives)
6. A hint button is available — limited uses based on word length
7. Guess all letters to win, or run out of lives to lose

## Features

- Hidden word entry (characters masked with `?`)
- Real-time Turtle drawing of the hangman figure as wrong guesses accumulate
- Hint system — reveals a random unguessed letter (max 2-3 hints depending on word length)
- Win and lose screens drawn directly in the Turtle window
- Clean Tkinter UI for input and buttons

## Tech Stack

- **Python**
- **Turtle** — hangman figure drawing and letter reveal
- **Tkinter** — UI windows, input fields, buttons
- **Random** — hint letter selection

## How to Run

```bash
# No external dependencies needed — all libraries are Python built-ins

# Run the game
python hangman.py
```

## Key Concepts Demonstrated

- Multi-window Python application (Tkinter + Turtle simultaneously)
- Dynamic drawing with Turtle based on game state
- String manipulation for letter finding and masking
- State management across nested functions
- Hint system with usage limits based on word length

## Gameplay Notes

- Hints are limited — 2 hints for words of 5+ letters, 1 hint for shorter words
- Press the hint button strategically — once used, that letter won't be hinted again
- F5 to restart a new game

---

**Author:** Vatsal Agrawal  
**GitHub:** [github.com/vatsal-agra](https://github.com/vatsal-agra)  
**LinkedIn:** [linkedin.com/in/vatsal-agrawal-a7a9641b0](https://linkedin.com/in/vatsal-agrawal-a7a9641b0)
