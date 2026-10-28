# Stone-Paper-Scissors
Write a Python program to play a Stone-Paper-Scissors game against the computer.  Requirements:  The user should enter their choice: "stone", "paper", or "scissor".  The computer should randomly choose one option.  

Overview

This is a simple Python console-based Stone, Paper, Scissors game where a user plays against the computer. The computer randomly selects one of the three options, and the program determines the winner based on the game rules.

Features
  ~Accepts user input for Stone, Paper, or Scissors.
  ~Randomly generates the computer's choice.
  ~Displays both user and computer selections.
  ~Determines the winner based on standard game rules.
  ~Handles draw situations.

Game Rules:
  ~Stone beats Scissors
  ~Scissors beats Paper
  ~Paper beats Stone
  ~If both players choose the same option, the game is a Draw.

Example Output:

    Options: Stone, Paper or Scissors
    Enter your choice: Stone
 
    User choice: STONE
    Computer choice: SCISSORS
 
    Stone beats scissors
    User WON

Logical Explanation:
~User Input:
  The program prompts the user to enter their choice and converts it to uppercase for easier comparison.
~Computer Choice:
  The computer randomly selects an item from a list containing the available options.
~Winner Determination:
  Nested if-elif statements compare the user's choice and the computer's choice to determine the winner. 
