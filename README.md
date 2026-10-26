# ATM-Simulator-using-Python
An ATM Simulator created using Python
# ATM Simulator Using Python

A console-based ATM simulator built in Python as a mini project for the Python Programming course at Chandigarh University.

## Features
- PIN login with 3 attempts (card is blocked after 3 wrong attempts)
- Check balance
- Deposit money
- Withdraw money (with insufficient balance check)
- Mini statement showing the last 5 transactions
- Input validation for wrong PINs, negative amounts, text input, and invalid menu choices

## Requirements
- Python 3.x
- No external libraries needed

## How to Run
1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Run:

```
python atm_simulator.py
```

4. Enter the PIN **1234** to log in. The starting balance is Rs. 10000.

## Concepts Used
Variables, functions, loops, if/elif/else, try/except, lists, the `global` keyword, and f-strings.

## Limitations
- Works for a single account with a fixed PIN.
- Data is not saved after the program closes.

## Future Improvements
- Save data in a file or database
- Support multiple accounts
- Add a change PIN option
- Add a graphical interface using Tkinter

## Author
**Jovanpreet Kaur**
UID: 25BCD10052 | Section: 25BCD1-B
Chandigarh University
