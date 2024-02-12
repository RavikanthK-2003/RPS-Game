# RPS-Game
Rock, Paper and Scissors Game with computer.
# About
We will ask the user to select either rock paper or scissors. And we will also make the computer choose one out of three randomly. Now we will check who won the game and give them a score. This is done 5 times to say who has won finally and we will ask the user if they want to continue or reset and continue or exit the game.
# Algorithm
1. Import the random module
2. Initialize the global variables for choices as a tuple of r, p, s, and computer score and player score as 0.
3. Create a function for getting the player’s choice.
    1. Inside the function get the input from the user.
    2. Check if the input is valid, If yes then return the answer to the function call. If no, then return the function call so that it will again ask for input from the user.
4. Create a function to return the computer’s choice as input from the random. choice function.
5. Create a game function inside which we will check who scores the mount for the current game.
    1. Call the player’s choice function and save the answer in a variable.
    2. Call the computer choice function and save it in another variable.
    3. Now, check if both the answers are the same, if so then print its a tie and no one gets a point.
    4. Following are the scenarios where the player gets a point,
        1. Player choice- “r” computer choice- “s”
        2. Player choice- “s” computer choice- “p”
        3. Player choice- “p” computer choice- “r”
    5. In all the other conditions computer scores a point.
    6. Now, print both the points to the user.
6. Now, in our main part of the program, we need to write a welcome message.
7. Call the game function 4 times for running the game for 4 rounds.
8. Ask the user if the user wants to continue/ reset and continue/quit.
    1. If the user wants to continue repeat step 7.
    2. If the user wants to reset and continue re-declare the variables for player score and computer score to zero and repeat step 7
    3. If the player wants to quit you can print thank you for playing and exit the game.
