---
title: CSE 1110 - Variables
layout: coursepage
---

Variables are names that represent values. In real life, you use names to refer to things. You do the same thing in programming. You can tell the computer that `X` will be 5.4, and from there on refer to X instead of 5.4. You can also change the value of X when needed.

Variables are dynamic types, meaning that you can declare them as any type that you want.

## Assigning
To assign a variable, simply use `=` to declare the new value associated with the name. For example:

    x = 12.3221

From that point on, you can reference `x` as a value.

    print x # will print 12.3221
    
This is also useful for states.

    ready = false

    def isReady():
        return ready

    def readyUp():
        ready = true

Other parts of the code might call `readyUp`, and then you will know that it is ready.

## Referencing
Variables have a **scope**. This means that if you create `x` inside of a method, it is only available in that method. Variables default to the *tightest* scope possible. For example:

    # State can be accessed anywhere in the file
    state = "working"

    def printState():
        # User state can't be accessed anywhere outside of method
        userState = "Is " + state
        print userState

Because `userState` is only created inside of the method, you cannot see it from anywhere else.

# Activity
Let's try doing this yourself. Create variables `name` and `age`, and make them your name and age. print out a message saying `Hello, **name**, you are **age**`. Answer available [here](http://frc-west.codepad.org/qczV36XG).

<iframe src="http://frc-west.codepad.org/" style="width: 80%; height: 550px"></iframe>
