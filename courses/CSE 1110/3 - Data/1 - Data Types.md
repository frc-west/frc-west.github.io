---
title: CSE 1110 - Data Types
layout: coursepage
---

Data is the building blocks of all computing. It tells the computer what to do, when to do it and how to do it. Most (if not all) of data is compromised of numbers. Those numbers are represented by 1s and 0s.

## Primitive
Primitives are values that are low level data types. They are typically the smallest memory wise. Their values in programming are directly represented, instead of being referenced like objects.

Python is different than most programming languages in that "primitive" values don't exist in the traditional sense. For all intents and purposes though, they work the same way.

### Boolean
A boolean value is on or off, 1 or 0. It is the smallest value.

### Integer
An integer value is a whole number from -2147483648 through 2147483647. Integers can be explicitly declared in python using `int(x)`. For a larger range of numbers, use `long`.

### Floating Point
Floating point numbers use [floating point](http://en.wikipedia.org/wiki/Floating_point) representations of decimal numbers for quick and cheap arithmetic and storage. They will not always yield perfectly accurate results, but are accurate for most use cases.

## Objects
In python, everything is an [object](https://en.wikipedia.org/wiki/Object_(computer_science)). They are instances of classes. Classes are outside the scope of this course, but if you wish to learn more about how objects are created and used, start [here](https://en.wikipedia.org/wiki/Class_(computer_science)).

### References
Objects are always references to the actual element in memory. Passing around an object through methods only passes an identifier telling the program where the object actually is. If the object is *mutable* (can be changed externally), changes made in one place will affect all other places where the object is referenced.

### Strings
A string is the based way to represent text in programming. In python, strings are created using two single or double quotes. ("like this" or 'this') They can also be created using `str(x)`, if the value is not a string in the first place. (numbers / booleans / other objects)

# Activity
Let's try doing this yourself. Create a function that returns the square of the number given. Print "Square of 18 is" and the answer. Answer available [here](http://frc-west.codepad.org/VKzRtuIf).

<iframe src="http://frc-west.codepad.org/" style="width: 80%; height: 550px"></iframe>
