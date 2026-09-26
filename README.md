# Week 5 Assignment: Password Generator & Your Own Module

## Assignment Overview

This assignment demonstrates how to use Python's built-in modules, create functions with default parameters, and build and import a custom Python module.

## Question 1: Password Generator

**File:** password_generator.py

This program uses Python's random and string modules to generate random passwords.

The make_password() function generates an 8-character password by default and can also generate passwords of a specified length, such as 12 characters.

## Question 2: Your Own Module

**File:** helpers.py

This module imports math and defines two functions:
- tables_needed() calculates the number of tables required using math.ceil().
- welcome() returns a personalized welcome message.

**File:** main.py

This program imports helpers.py and calls its functions to demonstrate how custom Python modules work.

## Expected Results

Running main.py should display:

```text
Welcome to PLP, Amina!
8
4
```

Running helpers.py independently should display:

```text
3
```

Running password_generator.py should generate two random passwords with lengths of 8 and 12 characters.

## Screenshots

Screenshots of two password generator runs, one main.py run, and one helpers.py run will be added after testing.
