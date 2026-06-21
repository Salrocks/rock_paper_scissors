#  Rock, Paper, Scissors🪨📄✂️

A simple command-line implementation of the classic Rock, Paper, Scissors game, built in Python. The user plays against the computer, with the computer's move chosen randomly and the winner determined using standard rules.

## Purpose📌 

This is a beginner-level Python practice project. The goal was to get comfortable with core programming fundamentals — conditionals, randomization, user input handling, and basic program flow — by building something small, interactive, and fun rather than just working through exercises.

## How to Play🎮 

1. Run the script.
2. When prompted, enter a number:
   - `0` → Rock
   - `1` → Paper
   - `2` → Scissors
3. The computer randomly picks its own move.
4. Both choices are displayed (with ASCII art!), and the winner is announced based on standard Rock-Paper-Scissors rules:
   - Rock beats Scissors
   - Paper beats Rock
   - Scissors beats Paper

## Skills Practiced 🛠️

- **`random` module** – generating the computer's move with `random.randint()`
- **`input()` handling** – capturing and converting user input from string to `int`
- **Conditional logic (`if`/`elif`/`else`)** – validating input and determining the winner
- **Lists** – using `action_list` to map numeric choices to readable names
- **f-strings** – formatting output cleanly
- **Multi-line strings** – storing ASCII art for visual flair
- **Program flow control** – using `exit()` to handle invalid input gracefully

## Running the Game🚀 

```bash
python rock_paper_scissors.py
```

Make sure you're running Python 3, since `input()` behaves differently in Python 2.
