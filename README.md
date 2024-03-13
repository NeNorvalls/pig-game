# Pig Game

## Deployed Version

- [Link to Deployed Version on Netlify](insert_link_here)

## Introduction

The Pig Game is a simple and entertaining dice game where players take turns rolling a die to accumulate points. The objective is to be the first player to reach or exceed a predefined winning score, usually 100 points. Players must decide whether to continue rolling to accumulate more points or hold onto their current score to avoid the risk of losing points.

## Technologies Used

- **Languages**: HTML, CSS, JavaScript
  - **HTML**: Used for structuring the game interface.
  - **CSS**: Used for styling and layout of the game interface.
  - **JavaScript**: Used for implementing the game logic and interactivity.

## How to Play

1. **Starting the Game**:
   - To start the game, simply click the "New game" button. This initializes the game and resets all scores to zero.
2. **Gameplay**:
   - Players take turns rolling a six-sided die by clicking the "Roll dice" button.
   - Each roll accumulates points based on the number rolled, except if a player rolls a 1:
     - Rolling a 1 resets the player's current turn score to zero, and their turn ends.
   - Players can continue rolling to accumulate more points or choose to hold their current score by clicking the "Hold" button.
3. **Winning the Game**:
   - The game continues until one player reaches or exceeds the winning score threshold (usually 100 points).
   - The player who reaches or exceeds the winning score first is declared the winner, and the game ends.

## Code Explanation

- The Pig Game is implemented using HTML, CSS, and JavaScript.
- The JavaScript code follows the principles of modularity and readability.
- Here's a breakdown of the key functions and elements in the code:
  - **Variables**: Declare variables to store game state such as scores, current score, active player, and game status.
  - **Initializing the Game (init)**: Sets up the initial conditions of the game, including resetting scores and hiding elements.
  - **Switch Player Function**: Handles switching between players after each turn.
  - **Roll Dice Functionality**: Rolls the dice, updates the current score, and checks for a rolled 1.
  - **Hold Button Functionality**: Adds the current score to the active player's total score, checks for a winner, and switches players if the game continues.
  - **New Game Button Functionality**: Resets the game to its initial state when clicked.
