# Bomb-and-Booster
Bombs and Boosters, modified version of Snakes and Ladders, features a 10x10 board where players roll dice to advance. The goal is reaching 100, but beware of bombs that impede progress. Boosters act as elevators, propelling you forward. 

## Authors
- Jubel Manoj Thomas
- Eliza Lesmana
- Karina Nathalie
- Arvind Singh Dhaliwal

## How to Run the Game

1. **File Requirements:**
   - Ensure all the following files are present:
     a. main
     b. startmenu
     c. playerbomb
     d. bombandbooster
     e. board
     f. positioning
     g. rollingdice
     h. animation

2. **Run the Game:**
   - Open the terminal and type:
     ```
     python3 main.py
     ```

## How to Play?

1. **Number of Players:**
   - Select the number of players (2 to 4) who will be participating in the game.

2. **Bombs and Boosters:**
   - Choose the position of bombs strategically. Landing on a bomb will set you back.
   - Player-placed bombs will explode if the player steps on them.
   - Discover randomly placed invisible boosters that propel you forward.

3. **Game Mechanics:**
   - Roll the dice on your turn.
   - Move forward the number of steps indicated by the dice.
   - The first player to reach position 100 wins the game.

## Game Files Explanation

1. **main.py:**
   - Runs the game in the correct order.

2. **startmenu.py:**
   - Displays the game start menu, allowing you to play or view the rules.

3. **playerbomb.py:**
   - Lets the user choose the number of players and position bombs.

4. **board.py:**
   - Prints the game board after each player's turn, showing bomb and player positions.

5. **bombandbooster.py:**
   - Places inputted bombs and random boosters on the board.

6. **rollingdice.py:**
   - Rolls the dice, simulating a random number from 1 to 6.
   - Handles bomb, booster, and end-of-game scenarios.

7. **positioning.py:**
   - Updates player positions based on the dice results.

8. **animation.py:**
   - Contains animations used throughout the game.

## Features of the Game

### Colored Output
- Differentiated colors for bombs, players, and boosters enhance visibility.

### Animations
- Aesthetically pleasing animations make the game more enjoyable.
- Note: Animated representations are not displayed due to documentation limitations.



Enjoy the Bomb-and-Booster game!

