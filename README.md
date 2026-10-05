# PLP Python Week 6 Assignment

## Assignment Title
Week 6 Assignment - Error Handling and Safe Functions

## Files

- `safe_tools.py` - Contains three safe functions that handle division, number conversion, and dictionary lookups without crashing.
- `unbreakable.py` - Demonstrates how `try/except` can keep a program running when the user enters invalid input.
- `README.md` - Describes the assignment and explains why an `if` check cannot catch `abc` on its own.

## Why can the if check not catch abc on its own?

An `if` check cannot catch `abc` when using `int()` because the conversion happens before the program can make a normal comparison. Trying to convert `"abc"` into an integer raises a `ValueError`, so `try/except` is needed to handle the error safely.