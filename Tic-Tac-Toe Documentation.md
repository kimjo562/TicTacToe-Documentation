| Joseph Kim|
| :---          	|
| s198022       	|
| Assessment: Tic-Tac-Toe  |
| C++ Assessment Documentation  |

## I. Requirements

1. Description of Problem
	- **Name**: Tic-Tac-Toe

	- **Problem Statement**: 
	Create a game using the C++ programming language and create a 2 player Tic-Tac-Toe Game.

	- **Problem Specifications**:  The game must include: Both player one or two Win condition, and a tie condition. Without Errors or Warnings.

2. Input Information
    - User input is needed to play and continue on the program.

3.  Output Information
    - **Number**: When the range is given, user input is needed for the computer what number is it trying to guess.
    - **Attempts**: Once the program and run and the computer has sucessfully guess it will print how many attempts it took before it got it right.
   

## II. Design
||
| :---          	|
|**Number Guess Diagram**
| ![Number Guess Diagram jpg](https://i.imgur.com/ThPOAHn.jpg)

Uses the two values to create a valid range for the computer to guess between. User then inputs the number to guess for the computer to find and loops until computer correctly guesses the number. At the end of the program, it will show how many attempts it took before getting it correct.
|
|:------------
|
| ![User Interface png](https://i.imgur.com/VHfEzjH.png)

Two values are set one low and one high to create a range, and then ask  a number for the computer to guess.
|
|:------------
|
| ![User Interface png](https://i.imgur.com/cZlAGNR.png)

When given a number a guess, the computer will try to guess and continue to loop until the computer has sucessfully found the correct number and the program will stop looping. It will show the amount of times it has looped as a way to print the amount of attempts taken.

2. ### Object Information

   **File**: Tic-Tac-Toe.cpp

     Description: The main body of the program and loops.
     
    **Attributes**

         Name: char[][]
             Description: Using a 2D Array to create a Tic-Tac-Toe Board.
             Type: char array 

         Name: playerTurn
             Description: Keeps account of whose player's turn it is, Player 1 is one Player 2 is two.
             Type: Integer

        Name: gameOver
             Description: When either players won or the game ended in a draw.
             Type: bool

        Name: position
             Description: Uses the numpad as the tic-tac-toe board, and puts the mark in the correct spot.
             Type: Integer

       