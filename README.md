This repository contains a Python function that calculates the average of a list of numbers. It addresses two common issues:

1. **Handling Empty Lists:** The function gracefully handles cases where an empty list is passed as input, returning 0 to avoid errors.
2. **ZeroDivisionError Prevention:** Although not directly demonstrated in this example, the function prevents a ZeroDivisionError by checking if the list is empty before attempting division.  Robust solutions might additionally check for the presence of only zero values.

The `bug.py` file contains the initial code, while `bugSolution.py` demonstrates a more robust approach.  This example highlights the importance of defensive programming in Python.