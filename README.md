# Mathdle Daily Equation Guessing Game

A Wordle-style daily puzzle game where you must guess a hidden arithmetic equation in 6 tries, with color feedback: green for correct digit in the correct position, yellow for correct digit in the wrong position, and gray for digits not in the equation.

## Features

- Daily puzzle seeded from the current date — same equation for everyone on the same day
- "New Random Game" button for unlimited extra practice rounds
- Valid guesses must be mathematically correct equations (e.g. 4*3=12 is accepted, 4*3=11 is not)
- Color-coded tile feedback after each submission: green (correct), yellow (present), gray (absent)
- On-screen keyboard with color state tracking (keys update to show best known state)
- Physical keyboard supported: digits, +, -, *, =, Backspace, Enter
- Equations use +, -, * operators with single- and double-digit operands and results
- Game state (guesses, result) persisted in localStorage — closing and reopening preserves progress for the daily puzzle
- Win/lose message with answer revealed on game over
- Smooth CSS transitions on tile reveals
