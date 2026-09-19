# RPG Character Creator

A simple Python program that creates an RPG character based on a name and three character stats: **Strength, Intelligence, and Charisma**.

This project was built as a Python practice project to work with **functions, conditionals, validation, strings, and basic arithmetic**.

## Features

* Creates a character with a name
* Assigns Strength, Intelligence, and Charisma stats
* Validates the character name
* Validates stat types and ranges
* Requires exactly **7 total stat points**
* Displays character stats using visual dots
* Provides error messages for invalid input

## Character Stats

Each stat is represented using 10 slots:

* `●` = assigned points
* `○` = remaining points

For example:

```text
Ehan
STR ●●●●○○○○○○
INT ●●○○○○○○○○
CHA ●○○○○○○○○○
```

In this example:

* Strength = 4
* Intelligence = 2
* Charisma = 1
* Total = 7 points

## Validation Rules

The program checks that:

* The character name is a string
* The character has a name
* The name is no longer than 10 characters
* The name does not contain spaces
* All stats are integers
* Each stat is between 1 and 4
* The three stats add up to exactly 7

## Example

```python
creation = create_character("Ehan", 4, 2, 1)
print(creation)
```

Output:

```text
Ehan
STR ●●●●○○○○○○
INT ●●○○○○○○○○
CHA ●○○○○○○○○○
```

## Concepts Practiced

This project helped me practice:

* Python functions
* Function parameters and arguments
* `return`
* `if` statements
* `isinstance()`
* String operations
* `len()`
* Boolean conditions
* Arithmetic operations
* String multiplication
* Input validation

## How to Run

Make sure Python is installed, then run:

```bash
python rpg_character.py
```

## Learning Project

This is a beginner Python project created as part of my programming practice and learning journey.
