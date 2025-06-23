# 🎮 Tic Tac Toe with Minimax AI
This is a simple terminal-based Tic Tac Toe game where you play as X and challenge a smart computer opponent (O) powered by the Minimax algorithm.

✅ Built entirely in Python. No external libraries required.

## 🧠 Features

✅ Human vs Computer gameplay

✅ Computer uses the Minimax algorithm to make optimal moves

✅ Detects wins, draws, and invalid input

✅ Runs in any terminal or command line

## 🖥️ How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/tic-tac-toe-minimax.git
```

2. Run the game

```bash
python tic_tac_toe.py
```

# Output demonstration is as follows

```py
PS D:\pycharm installed\procject\.venv\Scripts> python .\tic_tac_toe.py
Tic Tac Toe vs Computer (You are X, Computer is O)
  |   |
-----
  |   |
-----
  |   |
-----
Enter row (0-2): 1
Enter col (0-2): 2
  |   |
-----
  |   | X
-----
  |   |
-----
Computer played:
  |   | O
-----
  |   | X
-----
  |   |
-----
Enter row (0-2): 1
Enter col (0-2): 2
That spot is taken.
Enter row (0-2): 0
Enter col (0-2): 1
  | X | O
-----
  |   | X
-----
  |   |
-----
Computer played:
  | X | O
-----
O |   | X
-----
  |   |
-----
Enter row (0-2): 1
Enter col (0-2): 1
  | X | O
-----
O | X | X
-----
  |   |
-----
Computer played:
  | X | O
-----
O | X | X
-----
  | O |
-----
Enter row (0-2): 0
Enter col (0-2): 1
That spot is taken.
Enter row (0-2): 0
Enter col (0-2): 0
X | X | O
-----
O | X | X
-----
  | O |
-----
Computer played:
X | X | O
-----
O | X | X
-----
  | O | O
-----
Enter row (0-2): 2
Enter col (0-2): 1
That spot is taken.
Enter row (0-2): 2
Enter col (0-2): 0
X | X | O
-----
O | X | X
-----
X | O | O
-----
It's a draw.
```
