# Attendance
I self study every day for a minimum of 2 hours. This is a log to keep a record of the hours and work.

I am studying my Masters of Computer Science at Georgia Institute of Technology with a specialization in Machine Learning. 

Not all of my work results in projects that I can list on a portfolio but this can at least log my efforts. My background is in mathematics (Bachelors degree) so this log is important while I self-study computer science on the side in conjunction with my Georgia Tech classes.

The goal is to use this to get a software devleopment or data analyst position so I can upskill while I am getting paid do it. I am transitioning from a career as a tenured teacher.

## Template for Attendance Logging:

**YYYY-MM-DD:**
**Topic:** 
**Purpose:**
**What did you do?**


**2022-01-01 - 2022-04-23:**
I am taking the Edx courses offered by Georgia Tech in conjuction with their Masters of Computer Science program. 

Course name: Introduction to Python Programming, using the same material as CS1301: Introduction to Computing at Georgia Tech.

**2022-04-24: **

**Topic:** Edx course -> Introduction to Object-Oriented Programming with Java I: Foundations and Syntax Basics
**Purpose:** I know Python but I am preparing for the other Edx course I will be taking on Data Structures and Algortithms which is taught in Java.
This course also teaches OOP in Java.
**What did you do?** Downloaded and set up Eclipse IDE, completed HW01 on Java basics. Check the "CS1331" file and look for HW01 for my coding solutions.


**2022-05-01:**

**Topic:** 
I completed and uploaded my Calculator.java application and uploaded it to GitHub. 

**Purpose:** 
To apply Java for the first time. So far I have been implementing code and sorting algorithms in Python but have not built any applications in Java yet.
This is my first time applying the Java syntax and OOP principles in any application.

**What did you do?**
It is a basic calculator application that adds,subtracts, 
multiplies, divides, and alphabetizes strings. It takes two integers or strings separated by a space in one line of input on the terminal. 
It demonstrates usage of a switch statement, Scanner and next for user input, parsing user input into workable data types (string to int), and the comparable class on strings.

**2022-05-08:**
**Topic:** Battleship Application Progress
**Purpose:** 
To recreate the classic game battleship where users place their ships on a grid board and then fire at their opponents to sink all their battleships.
**What did you do?** 

So far I have set up the game so players can place their five 1-unit long ships onto their 5x5 gridfield. Scanner takes in two integers seperated by a space as the coordinates of each ship.
I also have prototyped my "turn" method where players pick a coordinate to shoot at and then it updates the "Location" board (did my ship get hit?) and the "Target" board for the other player to know 
where they have fired, and whether they have hit or missed. The boards then print to the terminal with 20 lines between each board to prevent screen peaking. 
I am currently debugging this turn method because my return function is only printing the place in memory where the Location and Target board arrays are stored rather than the actual boards themselves.


**2022-05-15:**
**Topic:**  Battelship Application Completed and my high powered laptop computer stops charging and won't turn on!
**Purpose:** To recreate the classic game battleship where users place their ships on a grid board and then fire at their opponents to sink all their battleships.
**What did you do?** 
I completed the battleship application which can be viewed in a separate repositiory. This involved the use of switch statements for input validation, along with plenty of data type conversions such as str->int, a nested do-while loop to count the remaining number of ships represented by the '@' character in a multi-dimensional char[][] array, use of the split function to split a string into an array that will be used as the location board for ships as well as the target tracking board to keep track of user hits and misses on the 5 x 5 playing grid. The highest dimenisional array used here was a 3 dimensional char array used to store both plaAyers' game boards where '@' is a ship that has not been hit, '-' is a space that has not been fired upon yet, 'O' is a space where the user has shot but missed, and 'X' is a spot where the user has hit. The game terminates after the program detects that one of the users has no ships left and prints to the terminal that the game is over and which specific player has won the game!
