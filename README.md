# Ravenworks Code
Repository for my own code and code that inspires or confounds me.

## This is the Python Library link for my reference which I will most likely use quite often as I learn to code in python.
https://docs.python.org/3/library/intro.html

## Hello World
Introduction to python coding. Learnt if I want something to print on screen then use the print statement.
https://github.com/Ravenworks6/research/blob/7c3f4cb84f85da5b07c043ce5d62c7e3b8ccfe4e/code/hello_world

## Dogs Age
To calculate the dogs age in human years.  The calculation is if the dog is 2 then it is 21 years and for every year after that age is x4.  I googled this one as I hadnt even started learning python let alone write a program.  The youtube video I watched on this was too complex for being a simple equation so I ended up cobbling it together instinctively.  It did not work because the float for the human age was not properly defined so I had some help from another student to correctly define the float for the human age.  It worked! but alas the calculation was incorrect because I did not subtract the 2 years from the dogs age.  Corrected this and started to understand the if and else statements.
https://github.com/Ravenworks6/research/blob/06081a8044f7f7bb22ee3795627782713018ce7a/code/dogs_age.py

## Magic 8 Ball
The user is to input a question they wanna ask the Magic 8 Ball and the program will randomly choose an answer from a pre-defined list of answers. Importing the random module to find a random answer from a list of answers.  Define a function called magic8ball() will generate and answer displaying it to the user. Inside the function it asks the user to ask/type a question then press any key for answer or quit to exit program. It is read using the input() and stored in the variable response and \n to print the sentence on a new line. Stored in Eightball_answers is a list of answers. Using the if and else statements to check if the input was quit or not.  If quit then the Have a Good Day is displayed and the program ends. If user presses any other key then a random answer from the list of answers is selected and displayed. random.choice of Eightball_answers is used for this and printed using the print().  After printing the answer a recursive call to magic8ball() is made to offer the user to ask another question or quit. This is not my code but I did add more answers to reflect all the possible answers of the original 8 ball.
https://github.com/Ravenworks6/research/blob/06081a8044f7f7bb22ee3795627782713018ce7a/code/magic_8_ball.py

## Wheel of Names
This program in the link has inspired me to try and recreate it https://wheelofnames.com/ But first I need to try and code it. I wanted to use the import random module somehow to pick a name from a list that is inputed by the user and have the program select a random name as the winner.

