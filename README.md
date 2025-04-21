---

# Rock Paper Scissors Game

## Description

**RockPaperScissor** is a simple Java console-based game that lets a user play Rock, Paper, Scissors against the computer. The computer randomly selects its move, and the result is decided based on classic game rules.

## Features

- User selects Rock, Paper, or Scissors using numeric input:
  - `0` – Rock
  - `1` – Paper
  - `2` – Scissors
- The computer randomly picks a move.
- The game outputs whether it's a win, loss, or tie.
- Validates the user input and handles invalid selections gracefully.

## Game Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- If both the user and the computer select the same option, it’s a tie.

## Requirements

- Java 8 or higher

## How to Run

1. Save the file as `RockPaperScissor.java`.
2. Open your terminal or command prompt and navigate to the file directory.
3. Compile the program using:
   ```bash
   javac RockPaperScissor.java
   ```
4. Run the program:
   ```bash
   java RockPaperScissor
   ```

## Example Output

```
Enter your choice 0:Rock, 1:Paper, 2:Scissor
1
2
Computer win
```

> _Note_: The number shown after your input is the computer’s randomly generated choice.

## License

This project is open-source and available under the MIT License.

---
