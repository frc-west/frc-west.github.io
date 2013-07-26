---
title: CSE 1110 - Debugging
layout: coursepage
---

Bugs are behaviours in a program that are not intended. The computer doesn't have the context to understand what to do with bugs, so your job is to "debug" it.

## Reading Stack Traces
The first step to debugging is finding out where the problem occurs. From there, you can print a stack trace to try and find out more.

<iframe src="http://frc-west.codepad.org/ABtrktfD" style="width: 80%; height: 250px"></iframe>

A stack strace goes back in time to the methods just recently called. It will tell you which line in the code it was, and display the actual code run. The last line is the exception message along with the exception type.

## Finding Errors
If something is going wrong with your program, you will need to find out where the problem is. If you know what the error happening is, that is useful. If not, it may be tougher. Try to locate the code that is doing the thing that is going wrong, and examine what could be going wrong. Sometimes, running only the specific code with example input can help localise the problem.

## Common Errors
There are some errors that occur very often. These are two examples.

### Off-By-One
Since programming uses a lot of zero-indexed numbers, off-by-one errors are common. These happen when the programmer goes one over or under the bounds of a range. Most commonly, this happens in for loops. Luckily, python has built in iteration so a lot of off-by-one errors are avoided.

### Not Declaring Variables
If you never declare a variable, the program can't access it. It's similar to words in English. If you've never defined what "going" means, it's difficult to understand phrases like "I'm going away".

Remember to tell the program what a variable is before using that variable.

# Activity
Let's try doing this yourself. Find the error that is happening in this snippet. Answer [here](http://frc-west.codepad.org/Dtwwbl6A).

<iframe src="http://frc-west.codepad.org/LFrLshdS" style="width: 80%; height: 550px"></iframe>
