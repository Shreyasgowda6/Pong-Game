# Pong-Game
A classic Pong game implemented in Java using Swing.


# Introduction
This Pong game is a simple implementation in Java using Swing components. It includes different classes for the game elements such as the ball, paddles, game frame, and score tracking.

# Classes
# Ball Class
The Ball class represents the ball in the game. It includes methods for setting the direction, moving, and drawing the ball on the screen.

# GameFrame Class
The GameFrame class extends JFrame and represents the main frame of the game. It sets up the game panel and initializes the game.

# GamePanel Class
The GamePanel class extends JPanel and represents the game panel. It includes the game loop, handles user input, and manages game elements such as paddles, the ball, and the score.

# Paddle Class
The Paddle class represents the paddles in the game. It includes methods for handling key events, setting the direction, moving, and drawing the paddles.

# PongGame Class
The PongGame class contains the main method and is responsible for launching the game by creating an instance of the GameFrame class.

# Score Class
The Score class represents the score display in the game. It includes methods for drawing the score on the screen.

# How to Play
Player 1 (Blue Paddle): Use the 'W' key to move up and the 'S' key to move down.
Player 2 (Red Paddle): Use the up arrow key to move up and the down arrow key to move down.
The game keeps track of the score for both players, and the first player to reach the maximum score wins.
