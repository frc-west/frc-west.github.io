---
title: CSE 1110 - Data Manipulation
layout: coursepage
---

There is a lot of ways to manipulate values. From basic arithmetic to calculus, there are many kinds of programming solutions.

## Calculations
A lot of the manipulation you will need to do is number calculations. There are a lot of applications for math in programming.

**Important**: Remember that calculations will always revert to the higher precision type. If both numbers are integers, an integer will be returned. Numbers are not rounded, they are floored.

### Addition / Subtraction
Adding and subtracting are the easiest operations. Simply use the `+` and `-` operators.

    print 12 - 3.4 # prints 8.6

### Multiplication / Division
Multiplication and division are just as simple as addition and subtraction, except for the type system. If you wish to do floating point operations, at least on value *must* be a float. Otherwise, answers will be rounded down. For example:

    print 12 / 5 # prints 2
    
But,

    print 12 / 5.0 # prints 2.4
    
You can use `float(x)` to transfer the number into a float too.

    print 12 / float(5) # prints 2.4

### Modulus
In programming, there is a mathematical operation that remains rarely used in traditional mathematics. Modulus returns the "remaining" value of a division. Some examples:

    12 % 5 = 2 # 12 / 5 = 2 R 2
    18 % 9 = 0 # 18 / 9 = 2 R 0
    18 % 10 = 8 # 18 / 10 = 1 R 8
    13 % 23 = 13 # 13 / 23 = 0 R 13

## Modifiers
There are a few basic modifiers for primitive values.

`+=`, `-=`, `*=`, `/=`, `%=` all perform a calculation on the variable. For example:

    x += 2

Will add 2 to `x`.

`not` reverses a boolean value.

    not True = False
    not False = True

# Activity
Let's try doing this yourself. Create a variable named `minutes` set to 458. Print the current time, assuming that the minutes started at midnight. Feel free to adjust the number of minutes to test your answer! Answer available [here](http://frc-west.codepad.org/jeue8Gra).

<iframe src="http://frc-west.codepad.org/" style="width: 80%; height: 550px"></iframe>
