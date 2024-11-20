## Slot Machine Game

This is a basic slot machine game built using vanilla JavaScript. It allows players to deposit money, place bets, spin the reels, and win based on matching symbols. The game runs entirely in the console and utilizes the prompt-sync library for user input.

# Features

	1.	Deposit Money: Players start by depositing an amount to set their initial balance.
	2.	Choose Bet Lines: Players can bet on 1 to 3 lines.
	3.	Place Bets: Place a wager for each line (limited by the balance).
	4.	Spin the Reels: Simulates spinning a slot machine’s reels with random symbols.
	5.	Determine Winnings: Calculate winnings based on matching symbols and the bet amount.
	6.	Play Again Option: Allows players to continue playing as long as they have a positive balance.

## Core Functionalities

# Counter Functionality

# The counter functionality ensures that the player’s balance is adjusted dynamically:
	•	Balance Deduction: Bets are deducted from the balance at the start of each round.
	•	Balance Increment: Winnings are added to the balance after each spin if the player wins.
	•	The game displays the updated balance after each round.

## Transposition Functionality

# The transposition functionality converts the columns of the slot machine into rows for easier evaluation:
	•	Input: A 3x3 grid where each column represents a reel.
	•	Output: A transposed 3x3 grid where each row corresponds to a potential winning line.

# For example:
	•	Reels (Columns):
    A | B | C
    D | B | C
    D | B | A

	•	Transposed Rows:
    A | D | D
    B | B | B
    C | C | A

## How to Run the Project

# Prerequisites

	1.	Node.js: Ensure Node.js is installed on your system. You can download it from Node.js.
	2.	Install prompt-sync:
	•	Run the following command to install the prompt-sync library:
    
    npm install prompt-sync

# Steps to Run

	1.	Clone or download the project files to your local machine.
	2.	Navigate to the project directory in your terminal:

    cd /path/to/project

    3.	Run the program with Node.js:

    node slot-machine.js

    4.	Follow the on-screen prompts to play:
        •	Enter a deposit amount.
        •	Choose the number of lines to bet on.
        •	Place your bet and spin the reels.
        •	Decide whether to play again after each round.

## Example Gameplay

    Initial Deposit

    Enter a deposit amount: 50

    Select Lines

    Enter the number of lines to bet on (1-3): 2

    Place a Bet

    Enter the bet per line: 5

    Spin and Results

    You have a balance of $40
    A | D | D
    B | B | B
    C | C | A
    You won, $20
    Your new balance is $60

    Play Again Prompt

    Do you want to play again y/n? y

# Future Improvements

	•	Add a graphical representation of the slot machine in the console.
	•	Introduce more symbols and dynamic paylines.
	•	Save game progress between sessions.
	•	Implement a leaderboard to track winnings.