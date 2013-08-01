---
title: Variables
layout: coursepage
---

Just like math, programmers use *variables* to represent data. These are, at the most basic level, just references to a certain piece of data. In the same way as you would do something like this in math:

    Let x be 13

You would do this same in programming:

    x = 13

A single equals sign declares the value of a variable. You can also change the value after the variable has been declared.

    x = 13
    x = 12

Variables can represent things like absolute constants, or changing parts of the program.

In python, there is no *type* of variables. They can be set to any kind of data that you want, whenever you want.

To check the type of the currently set value, use `isinstance()`:

    if(isinstance(x, float)):
        print("Yup, you're good")
