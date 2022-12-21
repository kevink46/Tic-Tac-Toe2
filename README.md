# Tic-Tac-Toe

Group Project ID: 1201 - Create the game Tic Tac Toe in Python

PROJECT DESCRIPTION

This is a mandatory group project part of the course "Programming - Introduction Level" supervised by Dr. Mario Silic.

The group project was done by Lucien Ledermann (Viper) and Kevin Kaufmann (kevink46).

The coding was done using Spider on Anaconda.

The goal was to create a simple Tic Tac Toe which is easy to play.

First, Player 1 can enter his name, followed by Player two entering his name. Afterwards, Player 1 begins playing through entering the field he would like to take. It is important that the exact same format is entered as it is used in the field, e.g. (2,2). As soon as Player one entered a field, the code checks wether the input is valid (one of the fields in the correct format). If the input is valid, the chosen field of player 1 gets an X and the code changes the value of the field in a seperate list from False to True. Therefore, from now on only fields which contain the value False can be taken. After player 1 took a field, player to can enter his preferred field. After entering a field, the code once more checks, if the input is valid and this time also checks wether the field is already taken. If the value in the sepe

The user can then choose an individual year (2007-16) to display other information (such as the country with the max. NNI and its value in that year, the country with the min. NNI and its value in that year, the mean NNI value of all countries in that year, as well as the median NNI value of all countries in that year).

NNI stands for Net National Income and is an economics term used in the accounting of national income. It is the difference between what is earned by nationals living inside and outside the country put together and non-nationals living in the country. It can be defined as NNI = C + I + G + (NX) + net foreign factor income - indirect taxes - manufactured capital depreciation where C = Consumption, I = Investments, G = Government spending and NX = Net exports (exports minus imports).

HOW TO USE AND TEST THE CODE

Four files are distributed within this repository.

This file (README.md) is used for a project description as well as insutrctions on how to use and test the code done by the student.

Two files contain code (AF_proj.py) and (AF_proj.ipynb). (AF_proj.py) is the file that is binding and shall be tested and used by the professor, whereas (AF_proj.ipynb) only provides the professor with an example of how the student functioned in the development of his code writing and testing.

A last file (NNI_Index.csv) is a modified file taken directly from the World Bank's website (shared above) which is read in the (AF_proj.py) file.

The file containing the code (AF_proj.py) also contains extensive comments for all or most of the coding lines. The comments should be read to gain deeper insight into the functioning of the code and logic used.

To test the project: The excel file (NNI_Index.csv) and (AF_proj.py) have to be downloaded and put in the same folder. The user then has to make sure she/he has functioning and latest python3 as well as pandas and NumPy libraries. By using the terminal, the user then open the file by accessing the folder (writing "cd ") and by sliding the folder which contains the files in the terminal and by then writing (AF_proj.py) if that is still the code file's name. Displayed will be an exemplary of the first 10 countries (alphabetically) in the list with corresponding values in some years. The user will then be prompted to enter a country's name (refer to line 19 - 22 of this file for explanations on what the code asks for inputs and expected outputs).

Hope you will enjoy the coding experience :)

Adrien Fesselet - Grimmgorthusgor

Student-ID: 14-605-521
