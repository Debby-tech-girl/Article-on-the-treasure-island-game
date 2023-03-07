# A STEP-BY-STEP GUIDE ON HOW TO SOLVE THE “TREASURE ISLAND” GAME USING PYTHON.


This lesson is targeted at giving a step-by-step guide on how to solve the “treasure island” game using Python. The game is one involving options that will determine the player’s fate (i.e you either fail or advance to the next stage).

This lesson will be given in six(6) simplified steps to give you a clear understanding of the game and how to code it and they are listed out below;

1. Understanding the game
2. Creating a new Python file
3. Drafting your algorithm 
4. Writing out your code
5. Testing/debugging your code
6. Sharing your code


### 1.UNDERSTANDING THE GAME.


The “treasure island” game as earlier stated is one involving options which determines the player’s fate. It involves different stages and the options might get more technical and wider as the game advances. 

It is worthy to note that at each stage, the player is faced with different options to choose from which will then determine if they’ve failed or moved on to the next stage. 

Here, we will be writing a simplified Python code on how to solve the “treasure island” game.


### 2.CREATING A NEW PYTHON FILE.


 Creating a new Python file on any text editor of your choice is essential as that is where the code will be written. For the sake of this lesson, we will make use of a python editor to write our codes.

A new Python file is created by  selecting the option “Python file” from the context menu, and then typing the new file name. A Python file is usually saved in the .py format 



### 3.DRAFTING YOUR ALGORITHM. 


An algorithm is a set of rules to be followed in calculations or problem-solving operations.

Drafting your algorithm helps you to have a clear understanding of how your program will go. 

Below is a draft of how your algorithm will be:

![The code](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipNsSYINGgWcn2Mf6v_2NCHpXR6aysdoWMm1Z1oL)

From the above, you can now have a clear understanding of how our game will look and how it will go. 

We will be working with the above algorithm to write our code.



### 4.WRITING OUT YOUR CODE.


This is where the programming takes place. For the sake of this lesson, we will be making use of various functions in Python. A function is a block of code which only runs when it is called. 

Data can be passed into a function as parameters. A function can return data as a result. 

In this step, our codes will be broken down and taken one at a time to help you understand it more.

![Diagram 1](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipMAy9cOrBVP_qka-TqlekKNAcxtfRs21jaEov7Y)

Above, we have invoked the print function. The print function prints out the specified message into the screen. It gives you what you feed into it. It works along with a pair of parenthesis () and quotation marks (“”).

![Diagram 2](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipPhg6zdkpx_B3nYuLHPHOBJ4vvY20DlfSgmysvM)

Here, we made use of a variable and we also invoked the input function.

A variable is created by assigning an object to it, the object can be referred to using the variable name. Assigning a variable is done using the assignment operator in Python (=). There are different rules for naming a variable, click for further study. 

The input() function takes input from the user and returns it. This means that when an input() function is invoked, it won’t proceed to the next line of code until the user has made an input. 

From the above, the user is prompted to either pick left or right, so the input() function gives room for the user to make a choice.

The .lower() function invoked helps to keep all the answers in lower case, this is because the options (left or right) are in lower cases and a user might capitalize the first word or the entire word. In Python, those are two different options.

![Diagram 3](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipM1n5bb0y-TIxEvYuORigihRzIGpXsbq6yD6XPz)


Here, we made use of the “if” statement which is a conditional statement that is used to determine whether a block of code will be executed or not. This means if the program finds the condition defined to be true, it will go ahead and execute the code block inside the if statement. 

Here the code block inside the “if” statement is print() function, therefore if it finds the condition true, it’ll go ahead and print out the code block. 


![Diagram 4](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipMk34iM-C5ygeJzUtV23Emc3n_HZ9E8h8hPJtHs)


Above it can be seen that we made use of an elif statement which is a short for else if and it is used when the first “if” statement used is not true but then you want to check for another condition. 

“If” statement usually pairs up with an “elif” and an “else” statement to perform a series of checks. 

From the above, if the “elif” statement is true, the code block embedded inside it will be executed. 

![Diagram 5](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipOmPbJg07__uVTQkuaSIk6FmA-HcTh6u50hazKB)


Here, we made use of the “else” statement which means, when the “if” statement and “elif” statement is false, the code block embedded in the “else” statement will be executed. 

From our algorithm, it can be said to be our “or anything else” option.


![Diagram 6](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipO9lnIBnHwRAaT9a4U9bA1bdCPJtoLOz88-rRzJ)


This should be more familiar now as we’ve made use of a variable and an input earlier on in this lesson. 

So here the variable “answer2” and an input() function was invoked.

It is worthy to note that we are working with our algorithm to create the game. 


![Diagram 7](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipOMXO52_jbZT2Po0g2Uz1IjEhJezlZGcMf8w7rh)


Just like the other “if” statement previously used, this is a conditional statement that only runs when the condition in it is met. 

Here, the “if” statement will only be executed if the user chooses “swim” in the input() function invoked.


![Diagram 8](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipMdMdZfGBxvTE4J09CKduG2JlqIgDOonpzrEtLR)


The “elif” statement is being used again. It works just like the one first used, the only difference are the parameters used in them.


![Diagram 9](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipP9JzU1YrCKhCcJOAnH1u0I9SV7djYWeID3h8Ak)


The “else” statement is used here, we’ve come across this already so we know it’s a conditional statement that runs only when the conditions in the “if” and “elif” statements are not met.


![Diagram 10](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipMf0_6io-2TLOS9djE2RZjrvjvfvt0912dm44x7)


We have come across variable and input() functions multiple times so we should be familiar with their functions and how they work. 

In this particular input() function, we have three conditions. 


![Diagram 11](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipPTBIZna2hOsy272mCbkL0NKO9YpJmNmglqbEee)


Here we are saying if the condition is true then the code block should be executed.


![Diagram 12](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipM29-fH3bU3vcitJTx0551g6oaLuidneaZlQbRM)


If the “if” statement above is false, then the program proceeds to the next line of code which is the “elif” statement. If the “elif” statement is true then the code block will be executed.


![Diagram 13](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipPyuj0O3PRw2LcugSOB-u2-apUeYRczLgori3LW)


If the condition of this “elif” statement is met, it will be executed.

If you notice, this is our second “elif” statement used along with the “if” statement, we can have multiple “elif” statements and only one “else” statement inside an “if” statement.


![Diagram 14](https://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipP5hhZMKyiw7lDfp1RmJjTUnn4sSNk8DUdLPDpMhttps://photos.google.com/album/AF1QipO6G6PE-3w3vwM9XVrHJbc3y0aC5jC3YSskrh7R/photo/AF1QipP5hhZMKyiw7lDfp1RmJjTUnn4sSNk8DUdLPDpM)


From the above, when all the other conditions are not met then the “else” statement is executed.



### 5.TESTING/DEBUGGING YOUR CODE.

This step is important as there are a lot of errors that can occur while writing out the program. 

Since Python is an interpreted language, it is executed line by line. This means that if it encounters an error, it will halt execution and present an error message on the console.

The most common error that can be found while writing your code are 
syntax error, 
indentation error,
name error

Syntax error occurs when the interpreter encounters an invalid syntax in code. Examples of syntax error are: missing a comma or a quotation mark or even misspelling a word. 

An indentation error occurs when the spaces or tabs are not placed correctly. This happens when you either indent a line of code that does not need to be indented or when you do not indent a line of code that needs to be indented. 

A name error occurs when you try to use a variable or a function that does not exist. For instance, we declared answer1 as a variable in our code, if we want to refer to our declared variable somewhere in our code and we write it as Answer1 it is a name error. 




### 6.SHARING YOUR CODE.


Now we have a fully functional game, you can now proceed to sharing it with your family, friends or colleagues. 

