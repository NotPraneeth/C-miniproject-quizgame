# FUN QUIZ GAME MADE WITH C
## can you become the millionare?
<img src = "assets/kbc.gif" >

## INTRODUCTION:
The code designed by us is a comprehensive and error-free Quiz Game Mini Project in. In this project, the user is presented with a series of questions and is offered a monetary in-game reward for each accurate response. In the quiz game, the questions are selected to encompass all aspects of a traditional quiz competition. Quizzes on science, technology, movies, sports, general health, geography, and other topics put the user's general knowledge to the test.

## EXPLANATION OF CODE AND WORKING:
We've broken this little project into many functions. We've aimed to cover all the major concepts such as file handling, arrays, loops, string functions etc.

* edit score () – adds the current cash prize won to the previous one upon giving the right answer to a question
* help () – help menu with game summary and rules
* reset score () – to reset the highest score/cash prize to default
* show record () – shows the highest cash prize won by a particular user
* show score () – to view the highest score

In this quiz game mini project, you can store the user name, view the highest score secured by a user, and even reset the score. Additionally, to make the game look a little more interesting, it is divided into two rounds; user must pass the first round to reach the second one.
Of the 2 rounds mentioned above, the first is called the Warm-up Round; the second is the Challenge round. In the warm-up round, the user is asked a total of three simple questions and they must be able to answer at least two of them correctly to enter the next round. If the user is not capable of doing that, he is not permitted to proceed further.
In the second and more interesting round of this quiz game in C, the user will be asked questions continuously, and for each right answer given, they will earn $100,000!
The game ends when the user’s cash prize piles up to $1 million. For each question asked, there are 4 options, namely A, B, C and D. There are no negative markings, so the user’s accumulated cash money won’t be deducted for wrong answers to the questions.

## OUTPUT:
![image](https://user-images.githubusercontent.com/92677364/175827712-fcda5ab1-9b7d-4b11-86d8-255f1e081dcf.png)

1) When we press S the game begins, you are asked to enter your name to start the game Of the 2 rounds mentioned above, the first is called the Warm-up Round; the second is the Challenge round. In the warm-up round, the user is asked a total of three simple questions and they must be able to answer at least two of them correctly to enter the next round. If the user is not capable of doing that, he is not permitted to proceed further.
In the second and more interesting round of this quiz game in C, the user will be asked questions continuously, and for each right answer given, they will earn $100,000!
The game ends when the user’s cash prize piles up to $1 million. For each question asked, there are 4 options, namely A, B, C and D. There are no negative markings, so the user’s accumulated cash money won’t be deducted for wrong answers to the questions.

2) When we press V the program displays the highest score recorded till that moment
![image](https://user-images.githubusercontent.com/92677364/175827800-b5d9c70b-4afc-4f44-9dc8-19f79065007e.png)

3) When we press H a list of instructions on how to play the game appears on the screen
![image](https://user-images.githubusercontent.com/92677364/175827849-e7c3cc81-f0fd-475d-ab73-87dc729ca1d3.png)

4) When we press Q the program helps the user to exit the ongoing game.


# CONCEPTS USED IN THE CODE:
### 1) IF-HANDLING: 
if statement is the most simple decision-making statement. It is used to decide whether a certain statement or block of statements will be executed or not i.e if a certain condition is true then a block of statement is executed otherwise not. 

Syntax: 
 
if(condition) 
{
  // Statements to execute if
   // condition is true
}
Here, the condition after evaluation will be either true or false. C if statement accepts Boolean values – if the value is true then it will execute the block of statements below it otherwise not. If we do not provide the curly braces ‘{‘and ‘}’ after if(condition) then by default if statement will consider the first immediately below statement to be inside its block. 

Example: 
 
if(condition)
statement1;
   statement2;
// Here if the condition is true, if block 
// will consider only statement1 to be inside 
// its block.
![image](https://user-images.githubusercontent.com/92677364/175828012-b4badbce-2ec2-416f-a090-f6119aef5d4a.png)

### 2)LOOPS:
In Loop, the statement needs to be written only once and the loop will be executed 10 times as shown below.  In computer programming, a loop is a sequence of instructions that is repeated until a certain condition is reached.
*	An operation is done, such as getting an item of data and changing it, and then some condition is checked such as whether a counter has reached a prescribed number.
*	Counter not Reached: If the counter has not reached the desired number, the next instruction in the sequence returns to the first instruction in the sequence and repeats it.
*	Counter reached: If the condition has been reached, the next instruction “falls through” to the next sequential instruction or branches outside the loop.

#### There are mainly two types of loops:  
* Entry Controlled loops: In this type of loop, the test condition is tested before entering the loop body. For Loop and While Loop is entry-controlled loops.
*	Exit Controlled Loops: In this type of loop the test condition is tested or evaluated at the end of the loop body. Therefore, the loop body will execute at least once, irrespective of whether the test condition is true or false. the do-while loop is exit controlled loop.

![image](https://user-images.githubusercontent.com/92677364/175828084-575a34a0-3045-476d-ad21-ed9944758be2.png)

### Loop Type and Description
* while loop – First checks the condition, then executes the body.
* for loop – firstly initializes, then, condition check, execute body, update.
* do-while – firstly, execute the body then condition check

### FOR LOOP:
A for loop is a repetition control structure that allows us to write a loop that is executed a specific number of times. The loop enables us to perform n number of steps together in one line. 
Syntax: 
for (initialization expr; test expr; update expr)
{    
     // body of the loop
     // statements we want to execute
}
![image](https://user-images.githubusercontent.com/92677364/175828143-f4704c3c-fa28-451b-8c8b-b92f7b617a7f.png)

### WHILE LOOP:
While studying for loop we have seen that the number of iterations is known beforehand, i.e. the number of times the loop body is needed to be executed is known to us. while loops are used in situations where we do not know the exact number of iterations of the loop beforehand. The loop execution is terminated on the basis of the test conditions.

Syntax: 

We have already stated that a loop mainly consists of three statements – initialization expression, test expression, and update expression. The syntax of the three loops – For, while, and do while mainly differs in the placement of these three statements. 

initialization expression;
while (test expression)
{
   // statements
 
  update expression;
}
![image](https://user-images.githubusercontent.com/92677364/175828168-8106209a-6c65-44ac-a5c9-59b4b092de25.png)

### DO-WHILE LOOP:
In do-while loops also the loop execution is terminated on the basis of test conditions. The main difference between a do-while loop and the while loop is in the do-while loop the condition is tested at the end of the loop body, i.e do-while loop is exit controlled whereas the other two loops are entry controlled loops. 
Note: In a do-while loop, the loop body will execute at least once irrespective of the test condition.

Syntax: 


initialization expression;
do
{
   // statements

   update expression;
} while (test expression);
![image](https://user-images.githubusercontent.com/92677364/175828181-4320330e-af9d-43f8-b1a6-0fe9a023e821.png)

### SWITCH CASE:
The switch statement allows us to execute one code block among many alternatives.
You can do the same thing with the if...else..if ladder. However, the syntax of the switch statement is much easier to read and write.

#### Syntax of switch...case:

    switch (expression)
     {
    case constant1:
      // statements
      break;

    case constant2:
      // statements
      break;
    .
    .
    .
    default:
      // default statements
    }
    
    
The expression is evaluated once and compared with the values of each case label.
* If there is a match, the corresponding statements after the matching label are executed. For example, if the value of the expression is equal to constant2, statements after case constant2: are executed until break is encountered.
* If there is no match, the default statements are executed.

### Input Output system:
Input means to provide the program with some data to be used in the program and Output means to display data on the screen or write the data to a printer or a file.
The C programming language provides standard library functions to read any given input and to display data on the console.
The functions used for standard i4.nput and output are present in the stdio.h header file. Hence to use the functions we need to include the stdio.h header file in our program, as shown below.

    #include <stdio.h>


Following are the functions used for standard input and output:
*	printf() function - Show Output
*	scanf() function - Take Input
*	getchar() and putchar() function
*	gets() and puts() function


### ARRAYS:
* It is a group of variables of similar data type referred by single element.
*	It elements are stored in a continuous memory location.
*	The size of array should be mentioned while declaring it.
*	Array elements are always counted from zero (0) onward.
*	Array elements can be accessed using the position of the element in the array*	Array can have one or more dimensions.

An array in C/C++ or be it in any programming language is a collection of similar data items stored at contiguous memory locations and elements can be accessed randomly using indices of an array.  They can be used to store collection of primitive data types such as int, float, double, char, etc of any particular type. To add to it, an array in C/C++ can store derived data types such as the structures, pointers etc. Given below is the picture representation of an array.

![image](https://user-images.githubusercontent.com/92677364/175828490-3cf3a940-2a94-4c6f-92e9-b3d8dbbda7fd.png)

![image](https://user-images.githubusercontent.com/92677364/175828494-74ef1449-4866-4831-b088-04b800594adb.png)

### STRING OPERATIONS:
Strings in C language are an array of characters ended with null characters (‘\0’). The null character at the end of a string indicates its end and the strings are always enclosed by double-quotes. In C language characters are enclosed by single quotes. Some examples of both of them shown below;
Example or Representation of C Characters and Strings
 * char string[10] = { ‘s’,’d’,’f’,’d’,’t’,’j’,’a’,’\0’ };
 * char string[10]=” fresher”;
 * char string[]=” fresher”;

There is a minor difference between the declarations of the strings in both of the above statements. Like when we declare char as string[10], 10 bytes of memory space gets allocated to hold the 10 values of string, while when we declare it like string[] then memory gets allocated at the time of execution of the program.



Function | Description
--- | ---
strlen() | Can compute the length of the string
Strcpy() | Can copy the content of a string to another
Strcat() | Is used to concatenate or join two strings
Strcmp() | Can compare two strings
Strlwr() | Can convert the string to lowercase
Strupr() | Is used to convert the letters of string to uppercase
Strrev() | Is used to reverse the string


# THANKS FOR STOPPING BY THIS PROJECT!
### THIS PROJECT WAS WORKED ON BY:
REGISTER NO | NAME
--- | ---
RA2111003011850 | RAYALA SAI PRANEETH
RA2111003011826 | AKANKSHA SANJAY SINGH



