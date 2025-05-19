# 🪨 Rock Paper Scissors – Terminal Game

## 🎯 Objective

Create a fully functional **Rock, Paper, Scissors** game that runs in the **terminal/command line** using Python.

The player will compete against the computer in a "Best of N rounds" format (e.g., Best of 3 or Best of 5). The game must track and display scores, round results, and allow the user to play again after the game ends.

---

## Features to Implement

1. **Ask for the Player's Name**
   - Display a welcome message using their name.

2. **Game Type Selection**
   - Ask if the user wants to play Best of 3 or Best of 5.

3. **Round-based Gameplay**
   - Each round, the player selects either `rock`, `paper`, or `scissors`.
   - The computer randomly picks a move.
   - Determine the winner of the round.
   - Update and display the current score.

4. **Rules of Winning**
   - Rock beats Scissors
   - Scissors beats Paper
   - Paper beats Rock
   - If both choose the same → it's a tie.

5. **Game End**
   - When a player reaches the majority of wins (e.g., 2 wins in best of 3), declare the winner.
   - Show game history: what was chosen and who won each round.

6. **Play Again Option**
   - After the game ends, ask if the user wants to play again.

---

## Functional Requirements

- Must use **functions** for different parts of the logic.
- Must use **loops** to repeat the game rounds.
- Use **lists** or **dictionaries** wherever helpful.
- Avoid using any external libraries except Python's built-in `random`.

---

## Sample Game Flow

```text
🎮 Welcome to Rock, Paper, Scissors!

Enter your name: Alex

Hello Alex! Choose game type:
1. Best of 3
2. Best of 5
Your choice: 1

🕹️ Round 1
Choose rock, paper, or scissors: rock
Alex chose: rock ✊
Computer chose: scissors ✌️
✅ You win this round!

Score: Alex 1 - Computer 0

🕹️ Round 2
Choose rock, paper, or scissors: paper
Alex chose: paper ✋
Computer chose: rock ✊
✅ You win this round!

🏆 Alex wins the Best of 3!

Game History:
Round 1: rock vs scissors → Alex won
Round 2: paper vs rock → Alex won

🔁 Play again? (yes/no): no

👋 Thanks for playing, Alex!
