# Tic-Tac-Toe Game (Python OOP)

A command-line Tic-Tac-Toe game developed in Python using
Object-Oriented Programming (OOP) principles.

## Features

-   Two-player gameplay
-   Interactive command-line interface
-   Player name validation
-   Custom player symbols
-   Input validation
-   Win detection
-   Draw detection
-   Restart game option
-   Clean object-oriented architecture

## Technologies Used

-   Python 3
-   Object-Oriented Programming (OOP)

## Project Structure

-   **Player** -- manages player information.
-   **Board** -- manages the game board.
-   **Menu** -- displays menus.
-   **Game** -- controls the overall game flow.

## OOP Concepts

### Classes and Objects

The project is organized into four classes: `Player`, `Board`, `Menu`,
and `Game`.

### Composition

The `Game` class owns: - Two `Player` objects - One `Board` object - One
`Menu` object

### Encapsulation

Each class manages its own data and behavior.

### Single Responsibility Principle (SRP)

Each class has one specific responsibility, making the code easier to
maintain.

## How to Run

``` bash
python tic_tac_toe.py
```

## Gameplay

1.  Start the game.
2.  Enter player names.
3.  Choose symbols.
4.  Take turns selecting cells.
5.  Win by matching three symbols in a row, column, or diagonal.
6.  Restart or quit after the game ends.

## What I Learned

Through this project I improved my understanding of:

-   Object-Oriented Programming (OOP)
-   Classes and Objects
-   Composition relationships
-   Encapsulation
-   Input validation
-   Exception handling
-   Game logic implementation
-   Separation of responsibilities (SRP)
-   Writing clean and maintainable Python code

## Skills Demonstrated

-   Python
-   OOP
-   Classes & Objects
-   Composition
-   Encapsulation
-   Input Validation
-   Exception Handling
-   Lists
-   Loops
-   Conditional Logic
-   Clean Code
-   Problem Solving

## Future Improvements

-   AI opponent
-   GUI using Tkinter or Pygame
-   Score tracking
-   Save game history
-   Colored terminal output

## Author

Rawan Ahmed

Computer Engineering Student

Istanbul Bilgi University
