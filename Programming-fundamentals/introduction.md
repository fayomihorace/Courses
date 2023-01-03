# Introduction to Programming fundamentals course
Welcome to this course where you will learn the fundamentals of programming.

Before we begin, let's set the context. Technology is deeply integrated into our lives today, 
with devices such as phones, laptops, and connected objects. This technology helps us automate
repetitive tasks and perform complex computations with little room for error. Additionally, 
with the development of artificial intelligence, there are even tools that are capable of kind of think
like humans. Kind of. However, that is not the focus of this course.

But all that is possile because we are able to talk to machines, to give them inputs, to give tasks
using programming.

So programming is: giving a set of instruction to a machine, in order to get a result of just to perform some work.
This set of instructions is also known as code.

Basically, a programmer writes a program using a programming language, and this program is then sent to a machine
with any necessary data to be executed. For example, when you type a message in WhatsApp and click the send button,
someone has written a program that is executed by the machine (most likely your phone) in the background.

Now that you know what programming is, it's important to note that:
- first: there are many different programming languages,
- and second: machines can only understand one specific language known as machine code.

However, machine code can be difficult for humans to write, so people have created more convenient and easy-to-use
programming languages known as high-level programming languages. That way, a programmer writes their program using a high-level
language and then passes it to a compiler, which translates the program into machine code and creates an executable
file that the machine can run. These programming languages are known as compiled programming languages:
Some examples of compiled pr lang include C, C++, and Java.


Now, there are other high level programming languages that as opposed to compiled pg lang, don't need to a compiler to 
create and executable machine code file before the machine can run it. Instead, the machine runs the program directly,
and the translation is done line by line as the program is being executed using what we call an `interpreter`.
These programming languages are known as interpreted programming languages

Examples: Python, PHP, Ruby, Python, and JavaScript...


Something to note is that, because interpreted languages programs do the transaltion job during programm run,
they tend to be a little bit slower than complied programs. However, the difference of speed is generally lower than a seconds,
and not noticeable in real application.
That's why, except in cases where extremely fast performance is critical, both compiled and interpreted languages can be used effectively.


Finally, it's important to note that each programming language has its own syntax and rules,
similar to how different spoken languages have their own grammar and sentence structure
The way you write a sentence in english is not the same for french, or chineess, or any other langauge.
The way to form sentences, the place of the subject, of the verb, etc are not the same.
It's the same thing in programming languages.

That's why, just as you need to learn the grammar and sentence structure of a spoken language in order to communicate effectively in that language,
you need to learn the syntax and rules of a programming language in order to write effective code

Let me show you some examples:

Example: Summing two numbers using machine code looks like this:
```
00: 0005   5
01: 0008   8

10: 8A00   R[A] <- mem[00]
11: 8B01   R[B] <- mem[01]
12: 1CAB   R[C] <- R[A] + R[B]
13: 9C02   mem[02] <- R[C]
14: 0000   halt
```

And doing the same using Java programming lang looks like this:

```java
int number_1 = 5;   
int number_2 = 8;  
int sum = number_1 + number_2;  
```

And with python prog lang we have something like this:
```python
a, b = 5, 8
sum = a + b
```

Don't worry if you don't totally understand the examples now, it was just to show you that the syntax are not the same.


For this course, most of the examples I'll give will be written in Python programming language, because it's the most popular and
easy programming language currenlty.



So, That is. to sumarize, programming is giving a set of instruction to machine (computer, phone, etc..) to perfomr some tasks wiht or without a result.


To summarize, programming is giving a set of instruction to machine (computer, phone, etc..) to perform some tasks wiht or without a result.
Machines only understand the machine code, so normally a program should be written in machine code.
However, since machine code can be difficult for humans to write, people have created high-level programming languages that are easier to use. Some of these languages are compiled, meaning that the program is translated into machine code before it is sent to the machine to be executed. Other languages are interpreted, which means that the translation occurs during the execution of the program.

Finally, each programming language has it own syntax and rules that programmer should follow while writting code in that programming language



Variable Declaration
Basic Syntax
Data Type and Structures
Flow Control Structures (Conditionals and loops)
Algorithms and Pseudo code
Functional Programming
Object-Oriented Programming
Debugging
IDEs and Coding Environments
Big O notation.



