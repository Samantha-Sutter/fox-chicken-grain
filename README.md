# The Farmer, Chicken, Fox & Grain Game
## About
This C# console application recreates the classic puzzle where a farmer needs to transport a chicken, a fox, and a bag of grain across a river. The challenge is to figure out how to move all three items across without leaving the chicken alone with the grain or the fox alone with the chicken. The game features a user interface that visually represents the banks of the river and the items' positions, providing an engaging way to solve this timeless puzzle.

## Technologies Used

- C#

## Features
- Visual representation of the game state with North Bank, South Bank, and the River.
- Interactive gameplay with user prompts for movement decisions.
- Game logic ensuring the puzzle's constraints are maintained (e.g., chicken eating grain, fox eating chicken).
- Win/loss conditions based on the player's decisions.

## How to Play
- The farmer, along with the chicken, fox, and grain, starts on the North Bank.
- The player must move the farmer and one item at a time across the river.
- The game provides feedback and checks if the player has won or lost after each move.

## Files
- Program.cs: Main entry point of the game.
- FarmerUI.cs: Handles user interface and game state display.
- Farmer.cs: Contains game logic and rules.
- Info.cs: Displays game information and instructions to the player.
