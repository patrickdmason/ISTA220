# C# Programming Homework 06 - Patrick Mason
## Chapter 06, C# Step by Step

## Readings
Read chapter 6 in the C# Step by Step book.
** 
## Discussion Questions
Answer the discussion questions for chapter 6 in writing.

### 1. What is an exception?
An unexpected condition during the execution of code that causes the program to fail. **A 'booboo'.** 
**
### 2. What happens in a try block if the program executes without errors? 
Nothing is passed to the exception handler and **the program moves to the next block of code.** 

### 3. How does the catch mechanism work for unhandled exceptions?
If a matching catch handler is found, the handler runs and execution continues with the first statement that follows the catch handler in the catching method. After catching an exception, **execution continues in the method containing the catch block** that caught the exception. 

### 4. What happens in a program if an exception block fails to handle a particular error?
If the runtime is unable to find a matching catch handler, **the program will terminate** with an unhandled exception. If there's no catch handler at the top enclosing block, the program crashes.

### 5. What is the parent class for all exceptions? How does this work?
Exceptions are organized into families called inheritance hierarchies. **Exception is the greatgranddaddy of all exceptions.** If you catch Exception, the handler traps every possible exception that can occur.

### 6. How do you determine the type of an error? **By capturing the Exception.Message property or Exception.GetType Method** 

###7 . What is the purpose of integer checking?
**To avoid allowing the calculation to overflow an integar value silently that is out of range** and returning a wrong answer.

### 8. What is the range of values than a signed Int32 type can contain? State the lowest value and the highest value. 
-2,147,483,648 to 2,147,483,647 **(int MinValue to int MaxValue)** 

### 9. What is the range of values that an unsigned Int32 type can contain? State the lowest value and the highest value. **0 to 4,294,967,295** 
### What is the difference between a signed integer and an unsigned integer? 
Unsigned integars aren't checked to make sure the integer value is within the range of possible values.  
### Can signed integers and unsigned integers represent the same amount of numbers? Yes
 
### 10. What does the finally block do?
**It ensures critical code always runs, even if an exception occurs.** 
It does this by ensuring the reader.Dispose statement executes and file handlers are made available again so you don't run out.

### 11. (Thought question) When would you not use a finally block in a try/catch construction? 
**When there's nothing to do after the code where the exception occurs.** 