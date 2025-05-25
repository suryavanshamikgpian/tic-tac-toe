# Tic-Tac-Toe

A classic Tic-Tac-Toe game implemented in C++ where you can play against a computer opponent using the minimax algorithm.

## Features and Functionality

*   **Two-Player Mode (Human vs. Computer):** Play against an AI opponent that uses the minimax algorithm to determine the best move.
*   **Clear Board Representation:** The game board is displayed in a user-friendly format in the console.
*   **Instructions:** Clear instructions are provided at the beginning of the game on how to make moves.
*   **Move Validation:**  Input validation ensures the user enters valid moves within the board's boundaries and available positions.
*   **Win/Draw Detection:**  The game accurately detects wins (row, column, or diagonal) and draws.
*   **Game Replay:** The option to play multiple games without restarting the application.
*   **Choice of First Player:** Players can choose whether they want to play first or let the computer start.

## Technology Stack

*   **C++:** The game is implemented in C++.

## Prerequisites

*   **C++ Compiler:** You need a C++ compiler (like g++, clang++, or Visual Studio) installed on your system to compile the code.

## Installation Instructions

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/suryavanshamikgpian/tic-tac-toe.git
    cd tic-tac-toe
    ```

2.  **Compile the code:**

    *   **Using g++:**

        ```bash
        g++ tik_tak_toe.cpp -o tic_tac_toe
        ```

    *   **Using clang++:**

        ```bash
        clang++ tik_tak_toe.cpp -o tic_tac_toe
        ```

    *   **Using Visual Studio:** Open the `tik_tak_toe.cpp` file in Visual Studio and build the project.
        Make sure you are using the C++ compiler.

## Usage Guide

1.  **Run the executable:**

    ```bash
    ./tic_tac_toe
    ```

2.  **Follow the on-screen instructions:**

    *   The game will display the board with numbers 1-9 representing available positions.
    *   You will be prompted to choose whether you want to start first (y/n).
    *   Enter the number corresponding to the cell where you want to place your 'X'.
    *   The computer will make its move, placing an 'O'.
    *   The game will continue until someone wins or the game is a draw.
    *   You will be prompted to play again or quit.

## Contributing Guidelines

Contributions are welcome! Here's how you can contribute:

1.  **Fork the repository:**  Create your own fork of the repository on GitHub.
2.  **Create a branch:** Create a new branch for your changes.
    ```bash
    git checkout -b feature/my-new-feature
    ```
3.  **Make your changes:** Implement your desired features or bug fixes.
4.  **Commit your changes:**  Commit your changes with a clear and concise message.
    ```bash
    git commit -m "Add: A descriptive commit message"
    ```
5.  **Push to your fork:**  Push your branch to your forked repository.
    ```bash
    git push origin feature/my-new-feature
    ```
6.  **Create a pull request:**  Submit a pull request from your branch to the main branch of the original repository.

## License Information

No license specified. All rights reserved by the original author.

## Contact/Support Information

For questions or support, please contact the repository owner through GitHub.
You can create an issue in the repository to report bugs or request new features.