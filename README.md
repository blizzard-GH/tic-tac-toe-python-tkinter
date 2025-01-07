Tic Tac Toe Game (Tkinter GUI)

A simple Tic Tac Toe game built with Python using Tkinter for the GUI. This project demonstrates basic GUI programming, event handling, and game logic implementation.

Overview

Tic Tac Toe is a classic two-player game where the goal is to get three of your marks (X or O) in a row, either horizontally, vertically, or diagonally. This project is built using Tkinter, Python’s built-in GUI library.

Features
	•	GUI built with Tkinter.
	•	Two-player turn-based game (Player X vs. Player O).
	•	Displays a message when a player wins or the game ends in a tie.
	•	Automatic board reset after each game.
	•	Simple, clean design using buttons for interaction.

Technologies Used
	•	Python (3.7+)
	•	Tkinter (for GUI)
	•	MessageBox (for game notifications)

Project Structure

.
├── main.py          # Main Python file for the game
└── README.md        # Project documentation

🛠️ Setup and Usage

Prerequisites
	•	Python 3.7 or higher
	•	A code editor (e.g., VS Code)

How to Run the Game
	1.	Clone the repository:

git clone https://github.com/yourusername/tic-tac-toe-tkinter.git
cd tic-tac-toe-tkinter


	2.	Run the game:

python main.py

How to Play
	1.	The game starts with Player X.
	2.	Players take turns clicking on the buttons to place their marks.
	3.	The game ends when:
	•	A player gets three marks in a row (horizontally, vertically, or diagonally).
	•	The board is full (it’s a tie).
	4.	A message box shows the result, and the game board resets automatically.

Code Explanation

The game is built using an Object-Oriented Programming (OOP) approach:
	•	Class: TicTacToe
	•	Main methods:
	•	__init__() – Initializes the game board and buttons.
	•	on_button_click() – Handles button clicks and updates the game state.
	•	check_winner() – Checks if a player has won.
	•	reset_game() – Resets the game board.

Improvements to Consider
	•	Add a single-player mode with an AI opponent.
	•	Customize the GUI with better colors and fonts.
	•	Add a score tracker to keep track of multiple rounds.

Screenshots

<img width="321" alt="image" src="https://github.com/user-attachments/assets/4cdd6c07-098f-4faf-84a2-ffc6bacc9584" />

License

This project is licensed under the MIT License. You are free to modify and distribute the code.

Contributions are welcome!
If you have ideas to improve the project, feel free to fork the repo and submit a pull request.

Contact : fay.abdillah@gmail.com

Show Your Support

If you like this project, please give it a ⭐️ on GitHub!

This README.md is designed to present your project professionally to recruiters or other developers checking your portfolio. Let me know if you want to tweak anything! 😊
