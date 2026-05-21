# Terminal-Based Tic-Tac-Toe Engine

A robust, Python-based implementation of the classic Tic-Tac-Toe game. This project is designed to demonstrate core software engineering principles, including Object-Oriented Programming (OOP), state management, and strict input validation to prevent runtime errors and unexpected behaviors.

---

## Technical Architecture & Logic

This application runs via the command-line interface (CLI) and focuses on clean architectural design and algorithmic efficiency.

1. **State Management:** The game board is managed using a dynamic array structure, tracking the state of each cell and evaluating winning conditions after every transaction.
2. **Input Sanitization:** Incorporates strict data validation mechanisms to ensure user inputs fall within acceptable bounds (integers 1-9) and prevents the overwriting of previously occupied cells, demonstrating a defensive programming approach.
3. **Algorithmic Evaluation:** Utilizes localized conditional logic to continuously scan rows, columns, and diagonals for sequence matches or draw states, ensuring high-performance execution with minimal time complexity.
4. **Modular Design:** The codebase is structured into logical components (board rendering, player switching, win condition checking), making it highly scalable for future algorithmic enhancements (such as integrating an AI opponent using the Minimax algorithm).

---

## Implementation Highlights

- **Language:** Core Python
- **Environment:** Command-Line Interface (CLI)
- **Key Concepts:** OOP, Input Validation, Exception Handling, Matrix Evaluation

---

## Execution Guide

1. Clone the repository to your local environment.
2. Ensure Python 3.x is installed on your system.
3. Run the main execution script from the terminal:
   ```bash
   python tic_tac_toe.py
