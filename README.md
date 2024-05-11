# Python Questions🚀

## Easy Level✅

# 1. What is Python?

- A high level programming language that uses an interpreter.
- We can have different paradigms in pyhton, such as OOP, functional, procedural and etc.
- It was invented in 1991 by Guido van Rossum.

# 2. What is a package in Python?

- Package is a way of storing related modules in a directory. There is also a special __init__.py file in the directory, 
which is an indicator that this directory should be treated as a package.

# 3. How do you define a variable in Python?

- Without specifiying the data type before setting it a name, which is unlike most other programming languages.

# 4. What is the difference between a list and a tuple in Python?

- lists are mutable, they are created with [] brackets. Tuples are immutable, they are created using normal brackets (). 
They both serve the purpose of storing data. In terms of efficiency, tuples are a better option since our interpreter knows
that the tuples are going to remain constant.

# 5. How do you check the length of a string in Python?

- You check the length of string in python by using the built-in function .len() 
before the instance of the string object. 

# 6. What is matplotlib in Python used for?

- It is a python library used for creating static, interactive, and animated visualisations in python. 
It can be used for generating plots, histograms, scatter plots, bar charts, and more, 
making it a powerful tool for visualisation and analysis. It also can be integrated with 
Pandas library, as well as NumPy.

# 7. How do you import the matplotlib.pyplot module?

- import matplotlib.pyplot as plt

# 8. How do you create a basic line plot using matplotlib?

import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [1, 2, 3, 4, 5]
plt.plot(x, y, )
plt.show()


# 9. How do you add labels to the x-axis and y-axis in matplotlib?

plt.xlabel("x axis")
plt.ylabel("y axis")

# 10. How do you save a matplotlib plot to a file?

plt.savefig("image.png")

11. What is a function in Python?

- In Python, a function is a block of reusable code that performs a specific task. Functions allow you to break down your 
program into smaller, modular pieces, making your code more organized, readable, and easier to maintain. Functions can take parameters, 
return sth, or apply modifications without returning a value.

12. How do you define a function in Python?

def function():
    function body 

    return result

13. What is the difference between the return statement and the print statement in Python?

return statement:

- The return statement is used inside a function to specify the value that the function should return as output.
- It is used to exit the function and pass back a value to the caller.
- A function can have multiple return statements, but only one of them will be executed when the function is called.
- The return statement is essential for functions that are designed to perform computations and produce results that need to be used or stored for further processing.

print statement:

- The print statement is used to output data to the console or other output streams.
- It does not return a value; instead, it displays the specified data to the screen.
- The print statement is primarily used for debugging purposes or for providing information to the user.
- It can accept multiple arguments and can print variables, strings, numbers, and other data types.

14. How do you check if a number is even or odd in Python?

    if num % 2 == 0:
        return True
    return False

15. How do you concatenate two strings in Python?

- with +

## Medium Level✅✅

1. What is pandas in Python used for?
2. How do you import the pandas library in Python?
3. How do you read a CSV file using pandas?
4. How do you select specific columns from a pandas DataFrame?
5. What is the purpose of the 'finally' block?
6. What is the purpose of the 'time' module in Python?
7. How do you work with dates and times in Python?
8. What is the purpose of the 'random' module in Python?
9. How do you generate random numbers in Python?
10. What is the purpose of the 'math' module in Python?
11. How do you perform mathematical operations in Python?
12. How do you sort a list in Python?
13. How do you open and read from a file in Python?
14. What is the difference between Python 2 and Python 3?
15. How do you take user input in Python?

## Difficult Level✅✅✅

1. What is numpy in Python used for?
2. How do you import the numpy library in Python?
3. How do you create a numpy array?
4. How do you write to a file in Python?
5. How do you calculate the mean of a numpy array?
6. What is the difference between 'is' and '==' in Python?
7. How do you create and use a virtual environment in Python?
8. What is the purpose of the 'init' method in a class?
9. How do you define and use class methods in Python?
10. What is a static method in Python?
11. How do you define and use a static method?
12. What is object-oriented programming (OOP)?
13. What are classes and objects in Python?
14. How do you define a class in Python?
15. What is inheritance in Python?
16. How do you implement inheritance in Python?
17. What is method overriding?
18. How do you use the super() function in Python?
19. How do you handle exceptions in Python?
20. What is the purpose of the try-except block?



