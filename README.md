# python_0x65 (Python 101)
Welcome to Python 0x65 (Python 101), a guided lesson for going from 0 to 101 in programming in Python.

We will be learning the basics of Python 3. This lesson will take about 2 hours. We'll cover absolute basics up through file reading. By the end, you’ll be a pro in the fundamentals of Python!

# Table of Contents
- [Installing Python](#installing-python)
- [The Command Line](#the-command-line)
- [The Python Interpreter](#the-python-interpreter)
- [Programming Fundamentals](#programming-fundamentals)
  - [Data Types](#data-types)
  - [Expressions](#expressions)
  - [Variables](#variables)
  - [Conditionals](#conditionals)
  - [Loops](#loops)
- [Programming with Python](#programming-with-python)
    - [Reading a CSV File](#reading-a-csv-file)
- [Let's Make Something](#lets-make-something)
- [Where to go from here?](#where-to-go-from-here)
- [Resources, Useful Links, and Sources](#resources-useful-links-and-sources)

# Installing Python
1. Go to <https://www.python.org/>
2. Go to Downloads: <https://www.python.org/downloads/>
3. Download the latest version of Python (Currently Python 3).
  - This is also often referred to as Python 3.x. Python 2.x is an earlier version that is very popular but is being phased out over time. There are a few [key differences and breaking changes](http://sebastianraschka.com/Articles/2014_python_2_3_key_diff.html) between Python 2 and Python 3.
  - Python 2 is still commonly supported for legacy applications and libraries. Even so, at this point [it's best to start with Python 3](http://www.asmeurer.com/blog/posts/moving-away-from-python-2/), since [almost all libraries support Python 3](http://py3readiness.org/).

# The Command Line
The command line is the window for a programmer to access the heart of a computer.

The Command Line is a CLI (Command Line Interface) as opposed to a GUI (Graphical User Interface). We'll be typing commands and sending that command to the shell by hitting the Enter/Return key.

Try it now by typing in (remember to hit enter to send the command!)
```shell
echo "Programming is really cool, wow!"
```
See that

## Getting around
Here are some absolutely essential


- `pwd`: "Print Working Directory"
- `ls`: "List Segments" or more colloquially, just "list"
- `cd`: "Change Directory"
- `man`: "Manual"

# The Python Interpreter
Let's boot up python! Python can either interpret new commands one the fly or run scripts you've already written.
  - Writing commands on the fly in the interpreter is great for experimentation and prototyping new stuff.
  - Running pre-written scripts is much faster and easier to re-run the same funcionality. You don't have to type in the same thing twice!

Let's start with writing some commands on the fly with the Pyhon Intepreter, which from now on we'll just call "the interpreter".

## Starting the Interpreter
We'll start the interpreter in *the shell*, which depends on which operating system you're on.

In your command line enter `python3` if you're Unix, or `py` if you're Windows.
When the Python interpreter boots up, it should output some starting information for you. See the following Unix and Windows examples for what to expect.

### Unix (Mac Terminal, `BASH` Shell)
```shell
george@testers-MBP:~$ python3
Python 3.6.1 (v3.6.1:69c0db5050, Mar 21 2017, 01:21:04)
[GCC 4.2.1 (Apple Inc. build 5666) (dot 3)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
### Windows (Command Prompt)
```shell
Windows PowerShell
Copyright (C) 2016 Microsoft Corporation. All rights reserved.

PS C:\Users\George> py
Python 2.7.13 (v2.7.13:a06454b1afa1, Dec 17 2016, 20:53:40) [MSC v.1500 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> quit()
PS C:\Users\George> # Notice that it defaulted to python 2 if you have both installed. Oops! Let's do Python 3 instead.
PS C:\Users\George> py -3
Python 3.5.1 (v3.5.1:37a07cee5969, Dec  6 2015, 01:38:48) [MSC v.1900 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```




## How do I exit the interpreter?
If you're in the interpreter and you want to get out, use the Python `quit()` function and hit enter.
```
>>> quit()
```
Alternatively, you can close the entire terminal window, but that is closing the entire shell, not just the interpreter running *inside* the shell.

## Print
The `print()` statement will be your best friend while programming.
Do you want to show the user some output? `print()` it.
Want to debug why your programming isn't working? Go ahead and `print()` the value

## The Interpreter as a Calculator
Let's try a few different things we can do with the Interpreter, which can easily act as a calculator.

```
>>> 1 + 1
2
>>> 4 - 15
-11
>>> 2 * 4
8
>>> 9 / 3
3.0

>>> (1 + 2.5) * .5
1.75
>>>
```

## Running Python Scripts
Let's run a Hello World script.

# Programming Fundamentals
Let's cover a few general concepts that every programming language has. These fundamental building blocks will allow us to build all possible programs.

- Data Types
- Expressions
- Variables
- Conditionals
- Loops

## Data Types
Numbers, Strings, and other types
## Expressions
Here are some expressions:
```
>>> 1
>>> "This string is an expression, albeit a simple one"
```

## Variables
## Conditionals
## Loops

# Programming with Python
## String formatting
https://pyformat.info/

## Reading from a file

## String slicing

## Reading a CSV File

# Let's Make Something
Now that we know how to do lots of cool things, let's program something real. Let's make a program which reads data from a CSV file and computes values from it.

# Where to Go From Here?
Python has extensive libraries for Scientific Analysis and Computation.
  - NumPy: A library for computation
  - SciPy: A library for scientific computation
  - RNASEQ: Compute RNA Sequences using Python.

# Resources, Useful Links, and Sources
- Main Documentation: https://docs.python.org/3/
- Tutorials: https://www.learnpython.org/
- Concise Overview of Python: https://learnxinyminutes.com/docs/python/
- Popular Libraries: https://pythontips.com/2013/07/30/20-python-libraries-you-cant-live-without/
