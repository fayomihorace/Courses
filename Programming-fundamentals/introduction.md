# Introduction to Programming fundamentals course

Hey, welcome to this course in which you'll learn the fundamentals of programmings.
So that make sense to explain first what programming is.

But before let's set the context.
Today technology is deeply intergrated in our lives. We have phones, laptops, 
connected objects. Technology is there to help us automate repetitive tasks, do
complex computations with almost no error. And more ever with AI there are tools
that can kind of think like humain. Kind of, but it's not the subject of this course.

But all that is possile because, we are able to talk to computers, to give inputs, to give orders
using programming.

So programming is: giving a set of instruction to a machine, wether it's a computer or a cell phone,
or a connected fridge, in order to get a result of just to perform some work.
That programm is also called `code`.

So basically, a person called the programmer write what we then call a program
using a programming language. And the program is sent to the machine with some
potential data to execute.

Example: When you enter a text into your whatsApp and cliks the send button, behind the scene,
someone has already written a program that will be executed by the machine which might probably be your
cellphone.

Now that you know what programming is, you should also know that,
first there are many porgramming languages.
and second, the machine or the computer understand only one programming language, which is called: `the machine code`.

But, we won't enter in the details in this course. You just need to know that machine code is not easy to write so people
has created more easier and convinient programming languages called high level programming languages.
THe programmer then write his program using the high level programming language, and passes it to something called a `compiler` that
will do the job of translating that high level program to the machine code and generate an executable file that the machine could run.
We call those programming languages: `Compiled Programming languages`.
Some example of such programming languages are: C, C++, Java.

Now there are other high level programming languages that are capable of translating program line by line into machine code
during program run. That means, the programer don't need to pass the program to a compiler before the machine could run it.
The machine can run that programm direcltly, line by line, but by doing the translaton job during the porgram run using what we call
an interpreter.
Those programming langauges are then called `Interpreted Programming Languges`.
Examples:

But, because interpreted languages programs do the transaltion job during programm run, they are generally slower than complied programs
which wait to have the final machine executable before start running. But, the difference is generally lower than a seconds, and you won't even notice
it with your eyes.
So excpet for really time perfomance critical tasks, both compiled and interpreted languages can be used.


Now the last thing you need to know to get started is that, each programming language has it own syntax and rules.
It's similar to speaking languages, the way you write a sentence in english is not the same for french, or chinees, or any other langauges.
The way to form sentences, the place of the subject, of the verb, etc are not the same.
It's the same thing in programming languages.
So to know a programming language, you need to know it syntax and rules.


Example: To summing two numbers using machine code looksl like this:
```
00: 0005   5
01: 0008   8

10: 8A00   R[A] <- mem[00]
11: 8B01   R[B] <- mem[01]
12: 1CAB   R[C] <- R[A] + R[B]
13: 9C02   mem[02] <- R[C]
14: 0000   halt
```
To do the same using Java it looks like this:
```java
int number_1 = 5;   
int number_2 = 8;  
int sum = number_1 + number_2;  
```

And now using python:
```python
a, b = 5, 8
sum = a + b
```
Don't worry if you don't get everything now, it was just to show you that as you can see the syntax are not the same.


For this courses, all the example I'll give will be written in Python programming languages. as it's the most popular and easy
programming language currenlty.



So, That is. to sumarize, programming is giving a set of instruction to machine (computer, phone, etc..) to perfomr some tasks wiht or without a result.
The machine only understand the machine code, so normally a program should be written in machine code.
But because machine code is not easy to write, people have created high level programming languges. Some are compiled that means the
program is translated into an executable machine code before sent to the machine,
and other are interpreted which means the translation occors during the program execution.
And finally, each programming language has it own syntax and rules that programmer shouls follow while writting code in that programming language



Variable Declaration
Basic Syntax
Data Type and Structures
Flow Control Structures (Conditionals and loops)
Functional Programming
Object-Oriented Programming
Debugging
IDEs and Coding Environments

