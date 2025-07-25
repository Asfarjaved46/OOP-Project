Instructions.txt
================

How to Compile, Run, and Use the Console Game Launcher Project
--------------------------------------------------------------

1. COMPILATION INSTRUCTIONS

This project is written in C++ and is designed for Windows systems. It can be compiled using any standard C++ compiler.

To compile using terminal (g++ example):
    g++ GameLauncher.cpp -o play 

To run the executable:
    ./play

Alternatively, you can use an IDE like Code::Blocks, Dev-C++, or Visual Studio to build and run the project.

--------------------------------------------------------------

2. PROGRAM FLOW OVERVIEW

After launching the program, the following steps occur:

STEP 1: LOGIN SYSTEM
- You will first see a login prompt.
- Enter your username and password.
- If your credentials are correct, you will proceed to the Main Menu.
- If login fails, you will be asked to try again.

STEP 2: MAIN MENU OPTIONS
After a successful login, you will see three options:

    1. Install Game
    2. View Games
    3. Exit

--------------------------------------------------------------

3. FEATURES DESCRIPTION

OPTION 1: INSTALL GAME
- This allows you to install a new game from the available options.

Available Games Include:
    - Tic Tac Toe
    - Hangman
    - Rock Paper Scissors
    - Plants vs Zombie
    - Snake Game	
    - Brick Breaker
    - Memory Game
    - Dino Game
    - Battle Ground
    - Treasure Hunt
    - Sudoku
    - Typing Speed Practice App
    - KBC
    - Flappy Bird

Each game is implemented using a class derived from a base 'Game' class with its own play() function.

OPTION 2: VIEW GAMES
- Shows a list of games you have installed so far.
- Allows to play installed games 
- Allows to uninstall the installed games

OPTION 3: EXIT
- This option cleanly terminates the program.

--------------------------------------------------------------

4. TECHNICAL NOTES
- This project demonstrates core Object-Oriented Programming concepts:
    - Inheritance
    - Polymorphism (via the virtual play() method)
    - Encapsulation and abstraction

- Game classes are modular, allowing future expansion.

- Console input/output and basic logic form the UI layer.

--------------------------------------------------------------

. END NOTES
- The game session resets after exiting the program.
