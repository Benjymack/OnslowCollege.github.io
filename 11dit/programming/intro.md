---
title: Intro to Swift
learning_intentions: ["To assign and use data stored in variables", "Printing text and getting user input", "Converting strings to numbers and back"]
success_criteria: ["You have created the 'Hello, student!' program, tested it, and shown your teacher that it works", "You have created the basic wall calculator program"]
---

# Task 1 Hello, student!

> **Filename**: hello.swift

## 1.1 Requirements

In this task, you will be asked to make a **very** simple program. Using Swift, you will:
-   Ask the user for their name.
-   Greet the user by their name.

## 1.2 First steps

In order to create the program:
- Open Visual Studio Code
- Click Open Folder and select the 11DIT Swift folder in your OneDrive
- At the top of the Explorer pane (top-left), click the New File button
- Create a new file called **Hello.swift**
- Write your code on the right
- Run your code by clicking the Run Swift File at the top-right

## 1.3 Statements to use

- ``print()``
  - This function will 'print' the text that is contained within the brackets and quotation marks to the screen
  - ```swift
    print("Hello, world!")
    ```
- ``readLine()!``
  - This function will 'print' the text that is contained within the brackets and quotation marks to the screen
  - The user then types something, presses Enter/Return, and whatever they entered is stored in a variable
  - ```swift
    let age = readLine("How old are you?")!
    ```

## 1.4 Example output

```
Please type your name: Bob
Hello, Bob!
```

# Task 2 Wall paint calculator

> **Filename**: paint1.swift

## 2.1 Requirements

In this task, you will do some simple maths to calculate how many litres of paint will be required to coat a wall. Using Swift, you will:

-   Ask the user for the width in metres of the wall
-   Ask the user for the height in metres of the wall
-   Tell the user how much paint is required in litres

For every square metre, the user will need 2 L of paint.

(Yes, this is excessive, but it's an exercise, go with it)
## 2.2 Statements to use

This task will involve casting. This means you will convert a variable from a string to an integer. To do this, make use of the ``int()`` function:

- ``Int()!``
  - This function converts strings representing a valid integer to a number type. You should store this in a variable
  - ```swift
    var age = Int("14")!
    ```
  - ```python
    print("How old are you?")
    var age = Int(readLine())
    ```
- Math operations
  - ``+`` to add two numbers together
  - ``-`` to subtract the right-hand side from the left-hand side
  - ``*`` to multiply two numbers together
  - ``/`` to divide the left-hand side by the right-hand side
  - ```swift
    let ageIn10Years = age + 10
    let ageLastYear = age - 1
    let doubleAge = age * 2
    let ageSquared = age * age
    let halfAge = age / 2
    ```

## 2.3 Hint

If maths isn't your strong point, don't worry. The formula for determining how much paint is needed for the wall is simple:
```
width * height * paint_per_litre
```

## 2.4 Example output

```
Please type the wall width in metres: 4
Please type the wall height in metres: 3

You will need 12 L of paint.
```

##### When you are finished, move on to [Next Steps](next-steps.md)