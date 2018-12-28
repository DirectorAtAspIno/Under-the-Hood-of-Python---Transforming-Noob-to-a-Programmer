# Under-the-Hood-of-Python---Transforming-Noob-to-a-Programmer
Project and Coding Lectures are made available here

# 1: Code to reveal the secret

What is the secret that we are going to reveal in this program?

We have some set of strings which are termed as secret words in our game, they are stored inside a specific Data Structure in python.¶
Now the python code that we write must pick up one of the secret word of its choice (which of course player shouldnt know to start with)from the stored data structure and respond back to the player with some hints about it.
For example - number of characters involved in that string could be one of the hints.
Following to which, the program must ask the player to guess each character present in the word - character by character and after each successful guess of the character, program must fill the corresponding position of the character in string and let the player continue to guess the remaining characters in string to reveal the program chosen secret word.
What if the guess goes wrong? Not to worry! our program must be kind enough to give some chance to the player, so in total there must be 7 lives or chances that the player must be given to guess the secret word.
If the player misses out all the given chances then the game gets over, secret word has to be revealed by the program and the player loses :(

