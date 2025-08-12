# TIC-TAC-TOE-java


---

**TicTacToe** ❌⭕
A classic **two-player Tic-Tac-Toe game** in the console, built with Java.

**Features:**

* 3×3 grid stored as a 2D `char` array
* Player **X** and **O** take turns choosing grid positions
* Input validation for correct row/column selection and empty spots
* Automatic win detection for rows, columns, and diagonals
* Declares a draw if the board fills with no winner
* Clear, text-based board display after every move

**How it works:**

1. Players alternate turns entering a row and column (0–2).
2. The game checks for a winner after each move.
3. If a player gets three in a row, they win.
4. If the board is full with no winner, the game ends in a draw.

**Requirements:**

* Java 8+
* Runs in any terminal or console

**To Run:**

```bash
javac TicTacToe.java
java TicTacToe
```

---

