# C# Programming Homework 07 - Patrick Mason
 Chapter 07, C# Step by Step
## Readings
 Read chapter 7 in the C# Step by Step book.
## Discussion Questions
 Answer the discussion questions in writing.
### 1. What is a class? 
According to the book, what does a class "arrange?"
A class is a type. It is the systematic arrangement of information and behavior into a meaningful entity. Classes 'arrange' information (data) and behavior into objects and methods.

### 2. What are the two purposes of encapsulation?
To combine methods and data within a class; in other words, to support
classification. To control the accessibility of the methods and data; in other words, to
control the use of the class.

### 3. How do you instantiate an instance of a class? How do you access that instance?
Use the class keyword to define (instantiate) a new class. It is accessed by using the NEW keyword, such as box b; b = New box();

### 4. What is the default access of the fields and methods of a class? How do you change the default?
The default access is PRIVATE, meaning a class's fields and methods are only accessible by other methods within the class, not from methods of other defined classes. The default is changed by using the PUBLIC keyword before before a class declaration.

### 5. What is the syntax for writing a constructor?
class [name]
{
private [FIELD_TYPE][FIELD_NAME];
// the following is the constructor:
public {METHOD_NAME]()
	{[PARAMETER = VALUE;}
}
It does NOT have a return type!

### 6. What is the difference between class fields and methods, and instance fields and methods? How do you
create class fields and methods?
Instance fields and methods don't require you to declare a new class for them each time they're used. However, tthey can't share their methods and fields with other instances of the class.

They're 'utility' methods. You create class fields and methods by declaring a class.

Class methods apply to ALL objects in the class. We create them by using the STATIC keyword.

### 7. How do you bring a static class in scope? Why would you want to bring a static class in scope?
You bring a static class in scope with the use of the STATIC keyword when you declare and name  the class. Bringing a static class in scope makes its methods accessible by using the name of the class.

### 8. Can you think of a good reason to create an anonymous class? What is it? 
When you only need to use its fields(?).


### 9. What is polymorphism as this term is used in computer science? This is not in the book.
Polymorphism is one of the four basic concepts of object oriented programming (inheritance, abstraction, polymorphism, and encapsulation). It refers to the ability of an object to have multiple interfaces; that is, to take on multiple forms. A child class object can be assigned to any class reference in its parent hierarchy.

### 10. What is message passing as this term is used in computer science? This is not in the book.
A technique for invoking behavior (i.e., running a program) on a computer. The invoking program sends a message to a process (which may be an actor or object) and relies on that process and its supporting infrastructure to then select and run some appropriate code.

### 11. What was the first object-oriented programming language?
Simula. Its purpose was designed for doing simulations.

### 12. Consider this quote by Alexander Stepanov:

"I find OOP technically unsound. It attempts to decompose the world in terms of interfaces
that vary on a single type. To deal with the real problems you need multisorted algebras
| families of interfaces that span multiple types. I find OOP philosophically unsound. It
claims that everything is an object. Even if it is true it is not very interesting | saying that
everything is an object is saying nothing at all.
Who is Alexander Stephanov? 

It brings up a good point, that calling everything an 'object' is oversimplification for the purpose of singular classification. By flattening the way of viewing reality and turning all concepts into objects, it causes reality to lack depth in favor of breadth.

### What do you think about this quote?

Alexander Alexandrovich Stepanov is a Russian-American computer programmer, best known as an advocate of generic programming and as the primary designer and implementer of the C++ Standard Template Library, which he started to develop around 1992 while employed at HP Labs