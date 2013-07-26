---
title: CSE 1110 - Structured Programming 1
layout: coursepage
---

Programming is the process or creating *programs*. By creating programs, people can do tasks much faster than by hand. Complicated calculations, repetitive actions and intense processing are all made easier through computer programming. But how do we take advantage of the power of computers?

## The Basics
Programming can be described in a few simple steps.

1. Write text representations of the program in a **programming language**.
2. Compile (or pre-compile) text into a binary executable file that computers can understand and run.
3. Test and debug program behaviour.

So how do these steps work? First, let's understand what a **programming language** is.
In the same way that linguistic language is a representation of ideas, a programming language is a representation of how a program should run. Programming languages can be understood as "recipes" for the computer.

For example, you might want to tell someone how to bake a cake. To do that, you'll need to describe the process of baking cake. You'd write **instructions**, saying "insert 2 eggs" or "bake at 370 degrees". Programming works just like that.

The main difference between English instructions and computer instructions is context. When you say "go outside" to a human, it is very easy to understand and do. The main reason for this is that humans are good at interpreting context. You know what outside is, how to get there, and what to do when you're there. The task is much more complicated when given to a computer. This is because it has no context.
The computer asks questions like:

* What's outside?
* What does go mean?
* How do I "go outside"?
* Which direction should I go to be outside?
* What kind of travel method should I use?

And it goes on and on.

This is both the best and worst part of computer programming. It is very good at doing things consistently, efficiently and repeatedly. It isn't good at assumptions. You need to explicitly describe everything to a computer.

A human might require these instructions to get milk

    Go to grocery store
    Buy milk
    Go home

Even those instructions are very verbose. "Go buy some milk" would probably suffice for most people.

An equivalent to a computer would be

    Travel to door
    Travel down 4th street until 16th ave
    Turn right
    Travel down 16th ave until grocery store
    Turn right
    Search for parking space
    Park in parking space found
    Travel to grocery store
    Search for milk aisle
    Travel to milk aisle
    Pick up one carton of milk
    Travel to cashier desk
    Purchase milk with money
    Travel in reverse from parking space (use 1 - 7)
    Put milk in fridge

And those instructions would still not have enough information in the real world.

In this course, we'll explore the fundamental ideas behind the instructions to give computer programs.

## This course
In this course, we'll use the [Python](http://www.python.org/) programming language. You don't need to install it, since we will use an online interpreter. If you wish to save your projects and learn on your own time, feel free to install Python and try it yourself.

Examples will be displayed like this

<iframe src="http://frc-west.codepad.org/Vsl72qwq" style="width: 80%; height: 600px"></iframe>

Feel free to play around with the code. Press the "create a new paste based on this one" to make your own version.
