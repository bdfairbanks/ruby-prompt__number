---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Numbers without decimals are called intergers.  Intergers can be further broken down into fixnum and bignum classes
Numbers with decimals are called floats.

# What are some common operations and comparisons you would perform on numbers?

all basic mathmatic funtions can be performed with ruby. Division is a little strange, as when the result of an operation is a decimal, Ruby will round unless a decimal place is
provided in one of the begining numbers. (10/3=3 10.0/3=3.33) Objects can also be assigned numeric value using the = operation.
Two numbers or sets of numbers or equations can be compared in true false fashion for equality, inequality, greater than, less than, greater than or equal to, less than or equal to.
There is another operation which test equality, greater than or less than with 0, 1 and -1 being the results given for each outcome.  All these comparisons function with the 
left object being the standard. 

# What is the difference between the `+` operation on a number versus on a String?

Fundementally they are the same, as they both combine two objects.  However the + using Strings results in string 2 being placed at the end of string 1,(string 1 + string 2 =string 1string 2)
while when dealing with numbers it just just adds them together.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

It will not work. I would use the .to_i method, then slap the mathmatical operation on the end. ("20".to_i/5)

# What is the purpose of the `times` operation? Is that the same as `*`?

The times operation is not the same as a *. .times is an iteration method, which in more basic terms means that it does something repeatedly.  The .times operation allows the programer to 
set the amount of times the iteration occurs, which seems useful.