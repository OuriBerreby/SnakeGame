# Snake Game

This project is an implementation of the Snake game in Java.

## Features

- Display the game **board** with the snake and the food.
- **Automatic movement** of the snake to the right at the start.
- **Control the snake** using arrow keys.
- The game **continues** as long as the snake doesn't touch the boundaries or bite itself.
- When the snake **eats food**, it **grows** by one unit and the **score increases** by 10.

## Project Structure

The project is organized into the following classes:

- `Board`: Represents the game board.
- `Game`: Manages the game flow.
- `Snake`: Represents the snake and its actions.
- `Coordinates`: Class to represent coordinates of a position.
- `Food`: Represents the food in the game.

## Usage

To run the game, execute the `Game` class which contains the `main()` method.

## Installation

1. Clone the repository:


2. Compile the Java files: javac il/co/lird/FS133/Projects/SnakeGame/*.java


3. Run the game: java il.co.lird.FS133.Projects.SnakeGame.Game

## Controls

Use the arrow keys on your keyboard to control the snake's movement:

- Up Arrow: Move the snake upwards.
- Down Arrow: Move the snake downwards.
- Left Arrow: Move the snake to the left.
- Right Arrow: Move the snake to the right.

## Game Over

The game ends under the following conditions:

- The snake touches the boundaries of the game board.
- The snake bites itself.

## Author

This project was created by Ouri Berreby.
