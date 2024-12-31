# Blackjack Game

This repository contains a simple Blackjack game implemented in Python. The game allows the user to play against the computer in an interactive console-based environment.

## How to Play

1. **Starting the Game**:
   - Run the Python script.
   - You'll be prompted to start the game by typing `'y'` for yes or `'n'` for no.

2. **Gameplay**:
   - The user starts with two cards, and the computer starts with one card visible.
   - The goal is to achieve a card total as close to 21 as possible without exceeding it.
   - You can choose to draw another card (type `'y'`) or pass (type `'n'`).

3. **Scoring**:
   - Cards are valued at their face value, except:
     - Aces (`11`) can be reduced to `1` if the total exceeds 21.
     - Face cards (`J`, `Q`, `K`) are worth `10`.
   - A total of `21` with the first two cards is a Blackjack and results in an instant win.

4. **Winning Conditions**:
   - You win if your total is closer to 21 than the computer's, or if the computer exceeds 21.
   - The computer will draw cards until its total is at least 17.

5. **Game End**:
   - The game ends when the user chooses to stop playing or if they exceed 21.

## Features

- Random card distribution using Python's `random` module.
- Automatic Ace value adjustment based on the player's or computer's total.
- Interactive prompts for gameplay decisions.
- Comprehensive scoring logic for both the user and the computer.
