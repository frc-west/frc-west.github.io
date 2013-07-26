---
title: CSE 1110 - Errors
layout: coursepage
---

There are two kinds of problems that can come up when programming. The first type is syntax errors. These are caused by programs that cannot be run because of something done that the language cannot do.

Typically, syntax errors are due to inexperience and unfamiliarity with a language. These show up less and less as you gain experience.

The second, more functional kind of error is a raised error. Raised errors are errors that happen during runtime. This means that something in your code has done something wrong/illegal. It's the programmer's job to tell the program what to do if the exception happens.

## Error Handling
In python, you should handle errors using standard procedures, and try to recover when errors occur. If it is completely impossible to recover, you should let the program die, printing debugging information.

### Catching Exceptions
Your program can detect when an error is thrown. You can do so using a try-except statement.

<iframe src="http://frc-west.codepad.org/tcaMPiWV" style="width: 80%; height: 250px"></iframe>

Anything inside of `try:` is run, and if the exception is thrown, the program goes into the `except`block.

In this example, an exception is *raised* immediately, triggering the `except` block. If there was no error raised in the `try:` block, the `except` block would not be run.

## Stack Traces
A stack trace is message giving a detailed look at the program execution before a certain point. Here's an example of a stack trace.

<iframe src="http://frc-west.codepad.org/ABtrktfD" style="width: 80%; height: 450px"></iframe>

## Error Messages
In the first example, an exception was created with a message as an argument. This message is for the programmer to explain what happened.

Access error messages using

    error.args[0]

As in:

<iframe src="http://frc-west.codepad.org/PALZuFgn" style="width: 80%; height: 300px"></iframe>

# Activity
Let's try doing this yourself. Create a method that raises an error, and call that method from another method, printing the stack trace. Answer available [here](http://frc-west.codepad.org/mB38GzZ5).

<iframe src="http://frc-west.codepad.org/" style="width: 80%; height: 550px"></iframe>
