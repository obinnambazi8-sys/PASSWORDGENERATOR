Project Overview

PyPassword Generator is a Python-based password generator that creates random passwords using a combination of uppercase letters, lowercase letters, numbers, and special characters.

The program allows users to customise the length and composition of their passwords by specifying how many letters, numbers, and symbols they want.

After collecting the user's preferences, the program randomly selects the requested characters, combines them into a list, shuffles their positions, and generates a final password.

The project was built to practise Python fundamentals, including loops, lists, functions, user input, randomisation, and string manipulation.

Features

Custom Password Length: Users choose how many letters, numbers, and symbols they want.

Uppercase and Lowercase Letters: Generates passwords using both character cases.

Number Generation: Includes randomly selected digits (0–9).

Special Characters: Adds symbols such as !, #, $, %, and &.

Password Randomisation: Uses random.shuffle() to mix the characters and make their order unpredictable.

Automatic Password Generation: Combines all selected characters into one password.

Technologies Used

Python 3 – Main programming language.

Random Module – Used to select random characters and shuffle the generated password.

How It Works

The program follows these steps:

Displays a welcome message.

Asks the user how many letters they want.

Asks how many symbols they want.

Asks how many numbers they want.

Randomly selects characters based on the user's input.

Stores the selected characters in a list.

Shuffles the list to randomise the character positions.

Uses "".join() to combine the list into a single password.

Displays the generated password.
