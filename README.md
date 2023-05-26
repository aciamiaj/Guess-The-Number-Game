# Guess-The-Number-Game

The Guess The Number Game is a simple console application that allows players to guess a sequence of randomly generated numbers. The game keeps track of the player's score based on the number of attempts taken to guess the correct numbers.

## Code Overview
The provided code snippet includes the following components:

Random Number Generation: The code initializes an array of integers called num and populates it with 5 random numbers between 1 and 49. The Random class is used to generate random numbers.

Stack Initialization: The code creates a stack called stack and pushes the random numbers from the num array onto the stack. The stack is used to keep track of the correct sequence of numbers.

Number Guessing Loop: The code prompts the player to guess the first number in the sequence and checks if the guess is correct. The loop continues until the player guesses all the numbers in the sequence.

Score Calculation: The code calculates the player's score based on the number of attempts taken to guess the correct numbers. The score is determined by subtracting the difference between the total attempts and the correct guesses from 1000.

## Usage
To play the Number Guessing Game, follow these steps:

Ensure that the necessary dependencies are included and the required classes (Random and Stack) are available.

Run the code in a console application environment.

The game will display the student's name and Humber ID.

The program will generate 5 random numbers and display them in ascending order.

The player will be prompted to guess the first number in the sequence.

If the guess is correct, the program will display a success message, remove the guessed number from the stack, and display the remaining numbers in the sequence.

If the guess is incorrect, the program will display a failure message and allow the player to try again.

The game will continue until the player guesses all the numbers in the sequence.

Once the game ends, the program will calculate the player's score based on the number of attempts and display it.
