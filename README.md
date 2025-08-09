# Game-Mania-JAVA-
CLI based JAVA project
Gaming Arcade
Welcome to the Arcade of ur 
Childhood Games
Games included are:
1.	Single Player Tic Tac Toe
2.	Multi Player  Tic Tac Toe
3.	Hangman
4.	Hand Cricket
5.	Rock Paper Scissors
6.	What Next?
7.	Guess the Riddle
8.	Mind Reader

1.	Single Player Tic Tac Toe:
Description:
Single player Tic Tac Toe is one of the most remarkable childhood games, in which 3 rows and 3 columns are available and we will be playing against the computer.
Whoever gets 3 in a row wins.
Working:
Single player tic tac toe is a simple game in which 3 rows and 3 columns are available and we have to trick the computer for making a row of 3 same objects.
Working of Code:
Firstly, we have declared a 1D Array for storing 'X's and 'O's , with respect to user choice and computer.
Initially I have entered numbers 1-9 in this array and displayed the tic tac toe grid and marked the positions with these numbers.
Using if conditional statement, we will compare user’s choice or computer’s choice with these numbers and respectively 'X' or 'O' will be market to that position and displayed in the grid on that specific position.
If that position is already occupied user will be informed to enter again.
This whole game is running in a while(true) loop and it will exit when a player/computer wins or it’s a draw.
Using if statements and logical operators we have compared all the possible solutions and if any condition is true, the loop exits using break statement.
User/computer turn is detected by variable "turn". If it is even then computer's turn else its user's turn.
For computer's choice, I have made an intelligence method which returns the position number according to game condition.
It is a defensive method which enters the third position for winning game if user has made 2 positions and there is a possibility of winning on that third position.
Switch statement is used for comparing positions and declaring the choice. 
Techniques used:
1. Loop Control Statements
2. Conditional Control Statements
3. Methods
4. Arrays
Classes used:
1. Main Class
2. Scanner Class
3. Math Class

2.	Multiplayer Tic Tac Toe:
Description:
Multi player tic tac toe is a simple game of two players in which 3 rows and 3 columns are available and we have to trick the other player in allowing us to make a 3 in a row.
Working:
Firstly, we have declared a 1D Array for storing 'X's and 'O's ,with respect to user choice and computer.
Initially, I have entered numbers 1-9 in this array and displayed the tic tac toe grid and marked the positions with these numbers.
Using if condition we will compare user’s choices with these numbers and respectively 'X' or 'O' will be added to that position and displayed in the grid on the position of that number.
If that position is already occupied user will be informed to enter again.
This whole game is running in while(true) loop and it will exit when a player wins or it’s a draw.
Using if statements and logical operators we have compared all the possible solutions and if any condition is true, the loop exits using break statement.
User turn is detected by variable "turn". If it is even then Player 2’s turn, else its Player 1’s turn.
Switch statement is used for comparing positions and declaring the choice
Techniques used:
1. Loop Control Statements
2. Conditional Control Statements
3. Methods
4. Arrays
Classes used:
1. Main Class
2. Scanner Class.

3.	Hangman:
Description:
Hangman is a game in which player has to guess a word letter by letter. The concept is that we have 6 chances and we have to save the person from hanging till death by guessing word. Each wrong guess brings him closer to death.
Working:
Firstly, I have made an object of file class to access the file with words. Then made an object of scanner class to read all the words from file. Then added all these words in an array list one by one.
Then we have used Math.random to randomly access any word from array list and by using loop we show dashes on screen equal to number of words. This random word string is converted into char array.
While loop is used for guessing word, it will end if user guesses the word or loses the game i-e, chances are over.
Then we have made another method to display the person that we have to save from hanging.
Another char array is declared of same length as word array and dashes are entered on each location for display and comparing. When user enters something firstly it is ensured that single character is entered and no digit is entered. Then whole array of word is checked on all positions one by one if user's guess matches any word.
If no character is matched life is detected. The characters which are matched with user's guess are shown on screen and entered in the array. Now it is checked if there are any dashes left in word i-e. any character left to guess then loop continues else it breaks and user wins.
Then if lives are 0 the loop breaks and user loses.
Techniques used:
1. Loop Control Statements
2. Conditional Control Statements
3. Methods
4. Exception Handling
5. File Handling
6. Arrays
Classes used:
1. Main Class
2. Scanner Class
3. ArrayList Class
4. File Class
5. IOException Class
6. Random Class

4.	Hand Cricket:
Description:
Hand cricket is a game that we used to play in our childhood. In this game first the toss is decided where  a player chooses heads or tails then chooses a number computer also chooses a number both are added if it is even, it is tails and if it is odd, it is heads. If user wins, he decides to bat or ball and if loses then computer chooses whether to bat or ball .... they both have choice from 1 to 6 if the numbers match batting one is out if not choice of score is added to score of the player (either user or computer ). 2 innings are played 
Scores are compared higher score wins !
Working:
This game is based on complex looping techniques. First of all, a set of rules is printed for user information then toss essentials are extracted from user for example what he chooses heads or tails and a number from 1 to 5!
Then computer choice from 1 to 5 is generated !
Then all the variables needed in the game are declared. Then on the basis of number 1 for heads 2 for tails selective toss loops are entered for example if chosen heads than if it is even than user loses if it is even user wins . Also, if user wins, check is iterated +1, if loses +3. This iteration is further used to separate the user winning loop and user losing loop.
If user wins, the user chooses if he wants to bat or bowl with the help of numbers 1 for batting 2 for balling, then user choice from 1 to 6 is entered and computer generates a number too between 1 to 6. If both score matches 2nd inning loop start where other has to start. For example, if user was batting, score matches, the loops break and computer starts batting. In first loop, user score was iterated with the choice before he was out and loop was broken. When broken computer’s score is iterated and if it reaches the target loops break and computer has won the game else user wins . It happens vice versa when user balls first. The one who wins is declared.
Techniques used: 
1.	Methods 
2.	Conditional Statements
3.	Loops 
4.	Nested loops 
       Classes used:
1.	Random class
2.	Scanner class
3.	Random class

5.  Rock Paper Scissors:
Description:
Basically, Rock Paper Scissors is a game of luck and chance. In this game, you have to choose 3 options.
1.	Rock
2.	Paper
3.	Scissors 
Rock crushes scissors.
Paper covers rock.
Scissors cuts paper.
In this way, each element crushes another  in a circular manner!
Working:
The game is run in a while loop which runs 5 times before the condition is met. User score, computer score and counter are defined before while loop because they are to be displayed outside the loop. In while loop, user has to choose 1 out of 3 elements and a computer choice is generated with the help of random class. Rest of the game works in if conditional statement. Each element is assigned a number 1, 2 or 3 and the desired loop is executed based upon the user’s choice. Inside each if condition, there are further 3 conditions which are for computer’s choice and comparison of user’s choice with the computer’s choice. According to the rules of the game, if user wins user score is iterated, if both chose the same element, it is a draw and if computer wins computer score is iterated. This process is repeated 5 times. 
When counter reaches the limit of the condition, while loop exits and user’s score and computer’s score are displayed then both are compared to decide who has won the game or is it a draw?
Techniques used: 
1.	Methods 
2.	Conditions 
3.	Loops 
4.	nested loops
Classes used: 
1.	Random class
2.	Scanner class
3.	Main class

6.  What Next?
Description:
What Next is a text based adventure game in which each choice leads to a certain consequence. A game that follows an original story line. A game that merely tests your decision making skills. If you choose wisely, you may win but if you choose incorrect, you may lose the game.
Working:
The coding begins with initializing the variables used within the game. The game starts within a while(true) loop.
First statement of the story is displayed along with certain choices using if-else conditional statements and from here the while story will be based upon our choices. When the desired option is chosen, the next part of the story is displayed and asks us to choose what happens next. Here two different options lead to two different outcomes and this continues throughout the game. The next three options must be chosen wisely in order for the player to survive for further game.
A certain point in the game reaches where computer generates a choice for us using Random class. If option 1 is chosen, the player survives and wins the game instantly. In contrast, if option 2 is chosen, the game continues displaying the rest of the story.
All of the working happens within a while(true) loop which breaks when the story line changes and remains to continue for a different story line.
A very interesting game for captivating the user using multiple choices.
Techniques used:
1.	Conditional statements
2.	Loops
3.	Nested loops
4.	Break statement
Classes used:
1.	Main class
2.	Random class
3.	Scanner class

7.  Mind Reader:
Description:
Mind reader is a personally favorite childhood game which my brother used to play with me. In this game, the computer asks the user to think of a word and it will guess it. A very interesting game which guesses every word the user thinks of despite its spelling or language.
Working:
The coding begins with initializing the variables and arrays used within the game. Two arrays are initialized with two different arrangement of the alphabets. When the game begins, the computer asks the user how many alphabets does the word contain. Then a matrix with a certain arrangement of the alphabets is displayed and asks one by one in which row does the first letter exists, then the second, the third and so on, till the last letter.
Then the second arrangement is displayed and again asks for the row numbers. When all of the rows are given to the computer as input, it displays the word and it all feels like magic. But the logic behind is that it compares the rows of both the arrangement and finds the common alphabet between them which gives us all the letters of the word that the user has thought of.
A very crafty game to catch people’s attention.
Techniques used:
1.	Arrays
2.	Loops
3.	Nested loops
Classes used:
1.	Scanner class
2.	Main class

8.  Guess the Riddle:
Description:
Guess the riddle is fun game for your brain in which you will have to guess single word answer of the riddle. If the user does not know the answer, he can take a hint but will lose a live. Computer will tell the user that the first letter of the word exists in the certain row and go search for it in the word cross puzzle.
A fun activity for your brain.
Working:
The coding begins with initializing the arrays for storing the coordinates of all the hints and an array for storing all the answers.
Then we are using File Handling to firstly create a file, providing it a proper path and then writing our riddles in it. After all the riddles are written within the file, we will close it. All of the creating and writing will be done in try-catch for handling the exceptions.
Then we will use 2 dimensional arrays to create the grid of the word cross puzzle and use nested for loops and conditional statements to display it.
Now, we will read the file that we have created. Initialize all the variables that will be needed further execution. We are using a while loop which will run for each line of the file one by one. Within the loop, we are declaring another scanner object which will be used for appending the answer given by user in an array. User will be given 6 lives. Then one by one each riddle will be displayed and user will be asked if he wants a hint or not. If he asks for a hint, a live will be deducted and the row will the told, if not then only the computer will ask for the answer. 
The program will check if the entered answer matches with the answers of the riddles that we have stored Earlier and increment counter variable by one. If user runs out of lives, the loop breaks and a message is displayed of the number of correct answers. All of the reading of the file will again be done in try-catch to handle the exceptions.
Techniques used:
1. Loops
2. Conditional Statements
3. Exception Handling
4. File Handling
5. Arrays
Classes used:
1. Main Class
2. Scanner Class
3. File Class
4. IOException Class
