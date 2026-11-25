# Task 5.3 – Build a Small Number Converter

## Objective
Create a Python program that converts a decimal number into binary and hexadecimal.

## Program
The program is saved as `number_converter.py`.

It takes a decimal number as input and uses Python's built-in functions to convert it into binary and hexadecimal.

## Test Results

| Decimal Input | Binary Output | Hexadecimal Output |
|---:|---|---|
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 100 | 0b1100100 | 0x64 |

## Functions Used

1. `input()` takes a number from the user.
2. `int()` converts the input into an integer.
3. `bin()` converts a decimal integer into binary.
4. `hex()` converts a decimal integer into hexadecimal.
5. `print()` displays the results.

## What I Understood

Binary conversion represents a number using only 0 and 1. Hexadecimal represents numbers using digits 0–9 and letters A–F.

The `bin()` function converts a number into binary, while the `hex()` function converts it into hexadecimal. Both functions include prefixes (`0b` and `0x`) in their output.

## Conclusion

I learned how to create a simple number converter using Python's built-in conversion functions.