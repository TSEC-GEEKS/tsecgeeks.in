---
layout: post
title: Getting Started with C Programming: Part 2
---

_Covers Setup, Basic Structure of Program, Hello World, Explanation of Terms_

+ Hey everyone, in this article I am going to continue the C Programming series in Turbo C. This is the second article in the series. If you haven't read the first one, you can click the link here : ____.



# Setup
+ Go to <https://www.onlinegdb.com/>
+ In the top left corner, Select 'Language' as "C (TurboC)" from the drop down menu. 
![OnlineGDB_TurboC](https://user-images.githubusercontent.com/46340124/163584994-c86cf4cc-e69a-4369-8d6d-d09ed0dd627a.png)
By default, onlineGDB loads in some code. You can delete this code and place your own code instead.
.................................

Now, last time we talked about header files, void main, printf, and getch().
This time lets talk about scanf, format specifiers, \n, comments, and variables.

# Comments
Comments are some of the most important parts of any program. Don't underestimate the comment. We write comments so that we can understand our code better. Try commenting your code while you write it.
There are two types of Comments in C: Single-line comments and Multi-line Comments.

## Single-line Comments
Single-line Comments start with two forward slashes (`//`).
Any text between // and the end of the line is ignored by the compiler (will not be executed).
See example of 
```c
// This is a comment
printf("Hello World!");
```

## Multi-line Comments
Multi-line comments start with `/*` and ends with `*/`.
```c
/* This is a 
Multi-line Comment.
As you can see
it streches across
Multiple lines.
*/
printf("Hello World!");
````


One thing that I highly reccomend you do is start any program with a COMMENT of what the program is, or the Problem Statement of the program. For eg, if you are told to "Write a Program to take User's Input and Print it out" you should put that as the first line of your program as a comment. Like this:
```c
// Write a Program to take a Number as User's Input and Print it out.
#include <stdio.h>
#include <conio.h>

int input
void main() 
{
  printf("Enter your Number: ");
  scanf("%d", &Input);
  printf("Your Number is: %d", Input);
  getch();
}
```
# Scanf
Scanf is a function, from `stdio.h`, that is used to take in input from the user. 
The scanf() function takes two arguments: the format specifier of the variable (%d in the example above) and the reference operator (&myNum), which stores the memory address of the variable.

## Format Specifiers
Format Specifiers are an important part of C and usually used with scanf. You might not have been explained what format specifiers for. 

**What is \n exactly ?**
The newline character (\n) is called an escape sequence, and it forces the cursor to change its position to the beginning of the next line on the screen. This results in a new line.

Examples of other valid escape sequences are: 
| Escape Sequence | Description                       |
|-----------------|-----------------------------------|
| \t              | Creates a horizontal tab          |
| \\              | Inserts a backslash character (\) |
| \"              | Inserts a double quote character  |













# Basic Structure of a C Program
```c
#include <header file name>
#include <header file name>
void main()
{
............
............
}
```
This is what the structure of a C program looks like.

# Your First C Program
Let's create our first C file.

Open OnlineGDB and type in the following code.

```c
#include <stdio.h>
#include <conio.h>

void main() 
{
  printf("Hello World!");
  getch();
}
```
Now Run the program by clicking the green 'Run' button near the top of your screen.

# Explanation of the Program

**What is `<stdio.h>` ?**

It stands for 'Standard Input Output'. stdio.h is a header file which has the necessary information to include the input/output related functions in our program. Functions like `printf` and `scanf` are from stdio.h.

**What is `<conio.h>` ?**

It stands for 'Console Input Output'. conio.h is a header file which is mostly used by MS-DOS compilers like TurboC. Functions like `getch()` are from conio.h and _won't work unless conio.h is included in the program_.

**What is `void main()` ?**

void main() is the entry point for execution in C program. It is where the main code of your program is written. 
> Main function is the heart of C program. Everything inside the main block will be code that is executed.

**What is `printf()` ?**

printf() is a function used to output text to the screen. In our example it will output "Hello World!".

**What is `getch()` ?**

getch() is a function used to keep the output from the program on the screen for some time until the user presses a key. Without getch(), we wouldn't be able to see the output of our program in TurboC as after execution the program would close.


# That Was Your First C Program
Congratulations! Now you know how to get started with C. 


---

If you have anything to add here, you can email me on the address given below.
Join our ~~WhatsApp Group~~ (edit: **REMOVED**)

---

Posted by Siddharth Bhatia