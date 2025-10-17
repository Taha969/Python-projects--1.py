Pong Game - Python Project using Turtle

This project is a classic implementation of the 2D Pong game, developed using the standard Python turtle graphics library. It is a simple two-player game where players control paddles to hit and deflect a moving ball.

🚀 Features

Two-Player Game: Each player controls a paddle on their respective side.

Score Keeping: A point is awarded when the ball passes the opponent's paddle.

Simple GUI: The turtle library is used to create the game window, paddles, and ball.

Colored Background (#359d9f)


⚙️ Requirements

To run this game, you only need:

Python 3.x

turtle library: This is a standard library included with most Python installations, so no additional installation is typically required.


▶️ How to Run

Save the Code: Save the provided Python code in a single file, for example, pong_game.py.

Execute: Open your command line (Command Prompt or Terminal) and navigate to the directory where you saved the file.

Run: Execute the file using the Python command:

python pong_game.py


🎮 Controls

The game is designed to be played by two players on the same keyboard.

Player

Movement

Key

Player 1 (Blue Paddle - Left)

Up

W

Player 1 (Blue Paddle - Left)

Down

S

Player 2 (Red Paddle - Right)

Up

Up Arrow (Up)

Player 2 (Red Paddle - Right)

Down

Down Arrow (Down)

📝 Main Code Structure

Setup: The game window is created, and its dimensions (800x600) and color are set.

Objects: The two paddles (player1, player2), the ball (ball), the center line (center_line), and the score display (score) are initialized.

Movement Functions: Functions for paddle movement are defined and bound to keyboard keys using window.onkeypress.

Game Loop: A continuous while True loop updates the ball's position, checks for collisions with walls and paddles, and updates the score when a goal is scored.
