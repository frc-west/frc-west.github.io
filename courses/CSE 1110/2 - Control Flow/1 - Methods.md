---
title: CSE 1110 - Methods
layout: coursepage
---

Fundamentally, programming relies on something called a "method". The concept of a method is basically a 'group of instructions' represented as one instruction. For example, "Walk forwards" involves "Move left leg forwards, then right leg forwards until distance is reached". Methods call other methods that perform parts of their functions.

In python, a method is represented like this:

    def plusOne(arg):
        return arg + 1

Use `def` to tell python that it is a method. `plusOne` is the method name. `arg` is the argument of the method. Use commas to denote multiple arguments. `:` is used after the parentheses to tell python that the next indented lines are the instructions of the method. Things that aren't indented are not part of the method. For example:

    def plusOne(arg):
    return arg + 1

    print plusOne(3)
    
This will report an error.

      Line 2
        return arg + 1
             ^
    IndentationError: expected an indented block
    
The instructions inside of `plusOne` need to be indented. This is the way python distinguishes normal instructions from instructions inside of methods.

## Managing Methods
Methods can become confusing if they are not managed correctly. Remember that there are principles that you should abide by to create usable programs.

### Reusability
Always make your methods as easily reusable as possible. Even if you don't think you'll need it again, it is good practise to make methods robust. This means that methods should do the exact same thing every time they are run. Most of this job is inherently done just because you can't change programs while they run, but it is still possible to break programs by making methods fragile.

### Generality
Methods should adhere to generality. Your `eatCake` method should be `eat` instead, and then you can call `eat(cake)`, and still have the capability to `eat(vegetables)`.

## Return Types
Methods can *return* values. This can be useful in a lot of cases. For example:

    def square(x):
        return x * x
        
By having a simple `square` method, you make it much easier to square numbers.

### Void
Sometimes you don't need to return a value. The term for this is a *void* method. In python, simply do not return a value to make a method void. Example:

    def printSquare(x):
        print square(x)

### Primitives
You can return any data type in a method. If the value is a *primitive* (number or boolean), it has to be assigned to a variable to be used elsewhere.

### References
If the return type is an *object* (non-primitive), it is a *reference* to the object. This means that the object is referenced instead of directly accessed like primitives.

## Parameters
Parameters, or arguments, are given inside of the parentheses in methods. They are given so that you can perform the function on the arguments. Otherwise, the method will always do the exact same thing. You make methods dynamic by using parameters. A lot of functions have inherent parameters, like the `eat` function. You need something to eat before eating, so `eat` requires `Food` (`eat(food)`).

### References VS Primitives
References and primitives can be confusing without context. This example should clarify the differences between the two:

<iframe src="http://frc-west.codepad.org/QLguiL9c" style="width: 80%; height: 800px"></iframe>

You can see that trying to adjust primitives inside of a method (`addOne`) does not work, but adjusting references does (`addHour`). For now, ignore what `Time` is. All you need to know is that it is an object that can be changed. The `time` object is a reference, and not a direct value.

# Activity
Let's try doing this yourself. Make a method named `foo` that will accept 1 value parameter, and prints it to the screen. Then, call this method. Answer available [here](http://frc-west.codepad.org/nQbx5cIW).

<iframe src="http://frc-west.codepad.org/" style="width: 80%; height: 550px"></iframe>
