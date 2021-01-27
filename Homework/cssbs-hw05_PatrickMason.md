C# Programming Homework Homework 05 - Patrick Mason

Chapter 05, C# Step by Step

Read chapter 5 in the C# Step by Step book.
Discussion Questions



1. What is a compound assignment operator? How does it work?
A compound assignment operator is a combination of an arithmatic operator with the assignment operator, which performs both assignment and arithmatic at once, eg. COUNT %= 3

2. List all the compound assignment operators. +=, -=, *=, /=, %=


3. List two ways to increment a numeric variable by 5. var = var + 5; var += 5; List two ways to decrement a numeric variable by 50. var -=50, var = var - 50


4. How long does a while loop run? ...for as long as the a condition statement is true.


5. What is an iteratiion variable? (Not in book)
An iteration variable is a variable that changes each time a programming loop executes and controls when the loop finishes.

6. What happens if you don't change the loop variable in the body of the while loop block?
The loop continues to run and never exits to the next line of code.

7. How many parts does a for loop statement have? Can you omit any of them? Can you omit all of them? What happens if you omit all of them?
Three: The initialization, the boolean expression, and the statement which updates the control variable. You can  omit any of them. No boolean expression defaults the FOR loop to true and the statement runs forever. Omitting the initialization and update statement creates a while loop.
for( init ; termination ; update )
{
do_stuff();
}

for( int i = 0; i < 1 numGrades; i++)
{
Console.Writeline("enter next grade");
grade = Console.Readline();
grades += process_grades(grade);
}

for( int i=0, j=1; j<100; j++)
{...}

8. How do you guarantee that a loop runs at least once?
...by using a DO statement, which evaluates the boolean expression AFTER each iteration instead of before.

9. What does the break statement do?
The BREAK jumps out of the body of an iteration statement and executes the first statement that follows the loop.

10. What does the continue statement do?
The CONTINUE statement causes the program to perform the next iteration of the loop immediately (after reevaluating the Boolean expression).

11. (Thought question) Can you think of any reason why you would want to have an infinite loop? An
"infinite loop" is a loop without an update variable that in effect runs forever. As you will see, these
kinds of loops are written intentionally to perform various kinds of tasks.
To run a web server or a motion detector.