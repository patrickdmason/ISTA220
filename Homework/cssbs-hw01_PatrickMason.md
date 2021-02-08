# C# Programming Homework 01 - Patrick Mason
Chapter 01, C# Step by Step
## Homework
## Readings
Read chapter 1 in the C# Step by Step book.
##Discussion Questions
Answer the discussion questions in writing for chapter 1.
### 1. What is a console app? 
A console application is an application that runs in a Command Prompt window instead of providing a GUI.
### 2. List two differences between . NET Framework and . NET Core. Note that in this class, we will be writing C# applications in . NET Framework and ASP.NET applications in NET Core. 
You use the .NET Core template for building portable applications that can also run on other operating systems, such as Linux. However, .NET Core applications do not provide the range of features available to the complete .NET Framework.
### 3. What does Main() (the main method) do in a console application? 
The Main method designates the program’s entry point.
### 4. Describe these three files: TextHello.sln, TextHello.csproj, and AssemblyInfo.cs. 
TextHello.sln is the top-level solution file. Each application contains a single solution file. A solution can contain one or more projects, and Visual Studio creates the solution file to help organize these projects. TextHello.csproj is the C# project file. Each project file references one or more files containing the source code and other artifacts for the project, such as graphics images. You must write all the source code in a single project in the same programming language. AssemblyInfo.cs is a special file that you can use to add attributes to a program, such as the name of the author, the date the program was written, and so on. You can specify additional attributes to modify the way in which the program runs.
### 5. What is the purpose of a namespace? 
Namespaces help solve the problem of recurring names and classes in large programs by creating a container for items such as classes. The fully qualified name is different with the inclusion of a namespace (path?) for the class.
### 6. Describe specically what using statements do. A using directive brings a namespace into scope. In the subsequent code in the same file, you no longer need to explicitly qualify objects with the namespace to which they belong.
### 7. What is the entry point for a console app? 
Where the Main method says it is, usually system. 
### What is the entry point for a UWP app? 
Where the App.xaml file says. In the rootFrame, "window.current.content"
### 8. What is an assembly? 
Libraries of compiled code that your application can use. When your C# code is compiled, it is converted into a library and given a unique name. In the Microsoft .NET Framework, these libraries are called assemblies.
### 9. How many different versions of the WriteLine() method does the Console class contain? 
19
### 10. What is the relationship between an assembly and a namespace?
### 11. What is a graphical app? 
An application whose interface requires non-console input, such as clicks, scrolls, etc.
### 12. What does Build do? 
Compiles the C# code, resulting in a program that you can run.
