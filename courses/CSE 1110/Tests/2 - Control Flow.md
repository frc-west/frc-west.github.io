---
title: CSE 1110 - Test 1 - Control Flow
layout: coursepage
---

### 1. How do you create a method?
1. With the `def` keyword
+ With the `var` keyword
+ With two parentheses
+ With a `:` symbol

### 2. How would you call this method?

    def foo(x, i):
        print x + i
        
1. foo("Hello, "World")
+ foo("Hello", 3)
+ foo("Hello", " World")
+ foo('Hello ' 'World')

### 3. Is this a valid method?

    def foo()
        print "FOO!"
        
1. True
+ False

### 4. What would the value of `x` be after running this program?

    def foo(x):
        x = 13
    
    x = 0
    foo(x)
    
1. 0
+ 1
+ 13
+ x

### 5. What would the value of `x.getValue()` be after running this program?

    def foo(x):
        x.setValue(13)
    
    x = Value(12)
    foo(x)

1. 12
+ x
+ 13
+ 0

### 6. What would the value of `x` be after running this program?

    x = 12
    def foo(x):
        x += 1
    foo(x)
    x += -1
    foo(x)
    x *= 2
    
1. 26
+ 22
+ 21
+ 12

### 7. What is `x` after running this program?

    if x > 0:
        x = 12
    else:
        x = 2
    
1. 12
+ 2
+ 0
+ None

### 8. How many times will this program print `x`?

    for x in range(10):
        if (x % 2 == 1):
            if (x > 1):
                print x

1. 1
+ 2
+ 3
+ 4

### 9. When running the program in #8, what is the output?

1. 3, 5, 7, 9
+ 3
+ 2, 5, 7
+ 2, 4

### 10. Will this program ever stop running?

    x = 0
    while x > 10:
        x += 11

1. True
+ False
