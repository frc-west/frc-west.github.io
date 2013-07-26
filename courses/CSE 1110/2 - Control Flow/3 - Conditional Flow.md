---
title: CSE 1110 - Conditional Flow
layout: coursepage
---

There are cases where going from step to step isn't sufficient for running your program. You want to be able to adjust behaviour depending of different factors. There are three (and a few more not discussed) main control flow adjustments that programmers use often.

## If
The most common way to adjust control flow is an *if statement*. This is equivalent to the English "if *condition* is true, do *instruction*".

In English:

    Let x be equal to 13.
    
    If x happens to be over to or equal to 13, print to the user "is >= 13".
    
In Python:

    x = 13
    
    if x >= 13:
        print "is >= 13"
        
You can see that if statements are easy to use for simple checks.

### Else

Sometimes you aren't content with one if check. Maybe there are multiple options, or you need to account for all other cases.

In English:

    Let x be equal to 24.3
    
    If x is less than 20, print to the user "< 20"
    
    If the previous statement wasn't true, and x is under 25, print to the user "< 25"
    
    If none of the previous statements were true, print to the user ">= 25"
    
In Python:

    x = 24.3
    
    if x < 20:
        print "< 20"
    elif x < 25:
        print "< 25"
    else:
        print ">= 25"

## For
For loops iterate over loops or through numbers. In python, there are two standard for loops.
The first type iterates over a range, starting at 0.

    for x in range(10):
        print x

Outputs
    
    0
    1
    2
    3
    4
    5
    6
    7
    8
    9

The second type iterates over a list of elements.

    for animal in ["dog", "cat", "mouse"]:
        print animal

Outputs
    
    dog
    cat
    mouse

## While
While loops run for however long a condition is true.

    while true:
        pass

Will run forever.

While loops use basically the same syntax as if statements, but loop over the instructions instead of running once.

    x = 0
    
    while x < 10:
        x += 1

Will run 10 times.

# Activity
Let's try doing this yourself. Create a variable named `age`. If that age is over or equal to 18, print `You can do anything!`, and if not, print `Sorry, not allowed in` 20 times. Answer available [here](http://frc-west.codepad.org/i7WjvOZ5).

<iframe src="http://frc-west.codepad.org/" style="width: 80%; height: 550px"></iframe>
