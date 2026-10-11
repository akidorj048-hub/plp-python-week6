# plp-python-week6

# PLP Python Week 6 - Safe Functions

This project demonstrates how to use Python try/except blocks to handle common errors safely.

## Files

- `safe_tools.py`: Contains three safe functions for division, number conversion, and dictionary lookups.
- `README.md`: Describes the assignment, its files, and the purpose of exception handling.

## Why can an if check not catch "abc" on its own?

An if statement can check a condition, but it does not automatically handle errors raised when converting invalid text to an integer. Calling `int("abc")` raises a ValueError, which can be handled using a try/except block.
