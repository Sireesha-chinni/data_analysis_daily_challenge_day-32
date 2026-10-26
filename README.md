# Day 32 – Python Coding Challenge

A set of six beginner-friendly Python exercises that practise core control-flow concepts: conditionals, `while` loops, `for` loops, counters, and basic output formatting.

## Repository Contents

| File | Description |
|------|-------------|
| `Day32_Coding_Challenge.pdf` | The problem statements for all six challenges |
| `Day-32-Data-analytics-challenge-python.ipynb` | Jupyter Notebook containing the solutions and sample outputs |

## Challenges

### Level 1: Understanding Logic

| # | Challenge | Concept | Description |
|---|-----------|---------|-------------|
| 1 | Even or Odd Checker | `if` / `else` | Takes a number and reports whether it is even or odd using the modulus operator (`%`). |
| 2 | Positive, Negative or Zero | `if` / `elif` / `else` | Takes a number and classifies it as positive, negative, or zero. |
| 3 | Print Numbers from 1 to N | `while` loop | Prints every number from 1 up to N. |

### Level 2: Real Thinking

| # | Challenge | Concept | Description |
|---|-----------|---------|-------------|
| 4 | Sum of First N Numbers | `while` loop + accumulator | Calculates 1 + 2 + … + N. |
| 5 | Password Retry System | `while` + `if` + counter | Prompts for a password and allows up to 3 attempts before stopping. Prints "Access Granted" on success. |
| 6 | Multiplication Table | `for` loop + formatting | Prints the multiplication table of a given number up to 10. |

## Example Runs

**1. Even or Odd**
```
Enter any number:24
Entered number is Even
```

**2. Positive, Negative or Zero**
```
Enter any number:55
Entered number is Positive
```

**3. Numbers from 1 to N**
```
Enter any number:4
1
2
3
4
```

**4. Sum of First N Numbers**
```
Enter any number:3
Sum From 1 to 3 is: 6
```

**5. Password Retry System**
```
Enter your Password:siri
Try Again
Enter your Password:<correct password>
Access Granted
```

**6. Multiplication Table**
```
Enter any number:5
5 * 1 = 5
5 * 2 = 10
...
5 * 10 = 50
```

## Requirements

- Python 3.9 or later
- Jupyter Notebook or JupyterLab (to run the `.ipynb` file)

## How to Run

1. Clone or download this repository.
2. Install Jupyter if you don't have it:
   ```bash
   pip install notebook
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook Day-32-Data-analytics-challenge-python.ipynb
   ```
4. Run each cell in order (`Shift + Enter`) and enter values when prompted.

## Concepts Covered

- Taking user input with `input()` and converting it with `int()`
- Conditional branching with `if`, `elif`, and `else`
- The modulus operator (`%`) for divisibility checks
- `while` loops with a manual counter
- Accumulator variables (running totals)
- Exiting a loop early with `break`
- `for` loops with `range()`
- Printing formatted output

## Possible Improvements

- **Input validation:** handle non-numeric input with `try` / `except ValueError`.
- **Password system:** show a "Too many attempts" message after the third failed try, and avoid hard-coding the password in the source.
- **Multiplication table:** use `range(1, 11)` so the table starts at 1 rather than 0.
- **Sum calculation:** avoid naming a variable `sum`, since it shadows Python's built-in `sum()` function.
- **Functions:** wrap each solution in a function to make the code reusable and testable.

## Author

Completed as part of the Day 32 Data Analytics learning challenge.
