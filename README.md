# blue_ball_survival

Title: Ball Drawing Simulation - Red or Blue?

# Description:

This Python program simulates a process where balls are drawn from two bags until only one remains. The goal is to determine the final ball's color (red or blue).

# Problem Statement:

There are two bags:

Bag 1: Contains 21 blue balls and 23 red balls.
Bag 2: Contains 22 red balls.
Two balls are drawn repeatedly from Bag 1. If the drawn balls are different colors, the blue ball is returned. Otherwise (both are red), both are removed, and a red ball from Bag 2 is added to Bag 1. This process continues until only one ball remains.

The code simulates this process and predicts the final ball's color.

# Instructions:

Save the code as ball_drawing_simulation.py.
Run the script using a Python interpreter: python ball_drawing_simulation.py.



# Output:

 **The program displays:**

Initial contents of both bags.
Each iteration of the drawing process:
Selected balls.
Removed balls (if applicable).
Added ball (if applicable).
Updated bag contents.
The final ball's color.

# Explanation:

**The code:**

Imports the random module for random selection.
Defines variables for ball colors and the number of iterations (initially set to 1).
Initializes lists representing the bags.
Shuffles the contents of Bag 1.
Prints initial bag contents and their sizes.
Uses a while loop to perform iterations until only one ball remains in Bag 1.
Inside the loop:
Prints iteration number and separator lines.
Randomly selects two balls from Bag 1.
Checks if the balls are different colors.
If different:
Removes the red ball (if one was drawn).
Prints removal and return of blue ball.
Prints updated Bag 1 contents.
If the same (both red):
Removes both balls.
Prints removal of both balls.
Appends a red ball from Bag 2 to Bag 1 (simulating adding a red ball).
Prints addition of red ball.
Prints updated Bag 1 contents.
Prints the final ball's color.
