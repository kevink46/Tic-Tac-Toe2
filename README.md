# Tic-Tac-Toe

Group Project ID: 1201 - Create the game Tic Tac Toe in Python

## Project description

This is a mandatory group project part of the course "Programming - Introduction Level" supervised by Dr. Mario Silic.

The group project was done by Lucien Ledermann (Viper) and Kevin Kaufmann (kevink46).

The coding was done using Spider on Anaconda.

The goal was to create a simple Tic Tac Toe which is easy to play.

## What does the program and how does it do it

First, Player 1 can enter his name, followed by Player 2 entering his name. After that the code creates the field.

Afterwards, Player 1 begins playing through entering the field he would like to take. It is important that the exact same format is entered as it is used in the field, e.g. (2,2). As soon as Player 1 entered a field, the code checks wether the input is valid (one of the fields in the correct format). If the input is valid, the chosen field of player 1 gets an X and the code changes the value of the field in a seperate list from False to True. Therefore, from now on only fields which contain the value False can be taken. If the input is invalid, the player gets the message "No valid input!" and has to enter again but in the correct format. 

After player 1 took a field, player 2 can enter his preferred field. After entering a field, the code once more checks, if the input is valid and this time also checks wether the field is already taken. If the value in the seperate list is False, it means that the field can be chosen and gets an O. Simontainously, the value in the seperate list changes to True. But if the value is already True which means that the field is taken, he gets the message "This field is already taken!" and has to take another field.

Now player one can take a second field and the procedure of the code is the same. 

This goes on until one of the players has either three fields in a row, in a column or in one of the two diagonals. The code therefore checks after every turn if the data in a row, column or diagonal is the same (either all X's or O's). If this is the case, the players get the message that one of them won. Should no one win, then the game stops after 9 rounds and they get the message that it is a draw and no one won. 


## How to use and test the code

There are only two files in this repository, which is the code itself and this file (README.md).

This file is used for the project description as well as insutrctions on how to use and test the code.

The file containing the code (code) also contains extensive comments for all or most of the coding lines. The comments should be read to gain deeper insight into the functioning of the code and logic used.

To test the project: The user has to make sure he has functioning python3. He can then copy the code and enter it in there. The following steps will guide you through the game:

1. Run the code
2. Enter the name of Player 1
3. Enter the name of Player 2
4. Player 1 can choose a field (eg. (2,2)
5. Player 2 can choose a field which is not taken already
6. Player 1 can choose another field and so on

We hope you will enjoy the game! :)

Lucien Ledermann and Kevin Kaufmann
