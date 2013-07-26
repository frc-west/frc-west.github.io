---
title: CSE 1110 - String Algorithms
layout: coursepage
---

Strings are the basic representation of text. There are a lot of different ways to manipulate, analyse and use strings.

## Concatenation
Concatenation is the combination of two or more strings together. In python, you do this using a `+` sign. For example:

    "Hello " + 'World' # is equal to "Hello World"

## Replacement
To replace any element in a string, use `str.replace(old, new)`

<iframe src="http://frc-west.codepad.org/pzRVlLbz" style="width: 80%; height: 250px"></iframe>

## Sub-strings
To get a string between two places in a string, use a substring. As is usual in programming, numbers start at 0, not 1.

<iframe src="http://frc-west.codepad.org/TL2AJoQX" style="width: 80%; height: 250px"></iframe>

As you can see, this method creates a string the is between index 0 (the start) and 3 (the 4th character).

You can also use the `find` method to make substrings even more useful.

<iframe src="http://frc-west.codepad.org/1KpIAc1N" style="width: 80%; height: 260px"></iframe>

# Activity
Let's try doing this yourself. Create an method that returns a string repeated `x` amount of times, with all `e` removed. Answer available [here](http://frc-west.codepad.org/HwCwBrDn).

<iframe src="http://frc-west.codepad.org/" style="width: 80%; height: 550px"></iframe>
