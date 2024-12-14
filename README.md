Number Guessing Game

This is a simple Python-based Number Guessing Game, where the player tries to guess a randomly generated integer within a specified range. The game provides feedback after each guess to help guide the player closer to the correct number.

Features

Random number generation within user-defined bounds.

Limited attempts based on the mathematical formula for optimal guessing.

Feedback for each guess (“Too low!” or “Too high!”).

Encourages user to try again if the correct number isn't guessed within the allotted attempts.

How It Works

The user is prompted to enter a lower and upper bound for the number range.

A random number is generated within this range.

The user has a limited number of attempts to guess the number, calculated as:

max_attempts = round(log2(upper_bound - lower_bound + 1))

After each guess, the program provides feedback:

If the guess is too low.

If the guess is too high.

If the guess is correct.

The game ends when:

The user guesses the number correctly.

The user exhausts the maximum number of attempts.

