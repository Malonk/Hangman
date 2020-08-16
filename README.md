# Hangman

## Game description
This game is called Hangman. 

The goal of the game is to guess the word the computer has chosen. 


## Rules
The computer will select a randomly chosen word from a list of sports. 

The user can guess one letter at a time. 

After each correctly guessed letter, the user can try to guess the whole word.

There's a total of 8 attempts to guess the word. 

If the user isn't able to guess the word within 8 attempts, the user loses the game. 


## Workflow
I started with a category of words from which the computer can pick one (a list of sports).

After this I drew the flow of the game and broke up the game into different isolated events, where possible. 

This allowed me to test various functionalities separately. 

The final part was to bring all isolated events into a game flow, which I struggled with the most. Therefore, the game is not finished unfortunately. 

## Learnings
For me, the main objective of writing this game was to be able to break down one big problem into smaller problems. 

Learning how to fix each problem on its own before bringing them together into one working flow. 

I've focused on creating functions and understanding how they work and how they should be integrated into a fully operating flow.

#### To improve
- Properly calling functions 

- Creating a fully functioning flow based on previously defined isolated events (functions)

- Understanding the full logic of loops and how/where to integrate them, so that the right functionalities are inside the loop

## Organisation
I used Jupyter Notebook to write the code. 

My repository consists of four files: 

- jupyter notebook "Hangman_python_game" : 1st version 
- jupyter notebook "Hangman_python_game_2" : 2nd version 
- readme file
- .gitignore