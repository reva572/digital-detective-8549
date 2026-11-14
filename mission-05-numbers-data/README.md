# Task 5.1 — Convert numbers by hand

# Decimal 13 to Binary
13/2 = 6, remainder 1
6/2 = 3, remainder 0
3/2= 1, remainder 1
1/2 = 0, remainder 1

Reading remainders from bottom to top:
13 (decimal) = 1101 (binary)

# Decimal 25 to Binary
25/2 = 12, remainder 1
12/2 = 6, remainder 0
6/2 = 3, remainder 0
3/2 = 1, remainder 1
1/2 = 0, remainder 1

Reading remainders from bottom to top:
25 (decimal) = 11001 (binary)


# Binary 1010 to Decimal
1010 = (1 × 2³) + (0 × 2²) + (1 × 2¹) + (0 × 2⁰)
     = 8 + 0 + 2 + 0
     = 10
1010 (binary) = 10 (decimal)


# Binary 1101 to Decimal
1101 = (1 × 2³) + (1 × 2²) + (0 × 2¹) + (1 × 2⁰)
     = 8 + 4 + 0 + 1
     = 13
1101 (binary) = 13 (decimal)


# Hexadecimal A to Decimal

A = 10
A (hexadecimal) = 10 (decimal)


# Hexadecimal 1F to Decimal
1F = (1 × 16¹) + (15 × 16⁰)
   = 16 + 15
   = 31
1F (hexadecimal) = 31 (decimal)


# Binary 1111 to Hexadecimal
1111 = (1 × 2³) + (1 × 2²) + (1 × 2¹) + (1 × 2⁰)
     = 8 + 4 + 2 + 1
     = 15
15 (decimal) = F (hexadecimal)
1111 (binary) = F (hexadecimal)



# Task 5.2 — Verify using Python
Used Python's built-in conversion functions to verify the manual calculations from Task 5.1.

Expressions tested and results:

1. `bin(13)` → `0b1101` 
2. `bin(25)` → `0b11001` 
3. `int('1010', 2)` → `10` 
4. `int('1101', 2)` → `13`
5. `hex(10)` → `0xa` 
6. `int('1F', 16)` → `31` 
7. `hex(int('1111', 2))` → `0xf`

My understanding:
Python provides built-in functions such as `bin()`, `hex()` and `int()` to convert numbers between different number systems. The results matched my manual calculations



# Task 5.3 — Build a Number Converter

Created a Python program named `number_converter.py` that accepts a decimal number and converts it into binary and hexadecimal.

Code used:

num = int(input("Enter a number: "))

binary = bin(num)
hexadecimal = hex(num)

print("Binary:", binary)
print("Hexadecimal:", hexadecimal)

TEST NUMBERS:
13 → Binary: 0b1101, Hexadecimal: 0xd
25 → Binary: 0b11001, Hexadecimal: 0x19
31 → Binary: 0b11111, Hexadecimal: 0x1f

# Task 5.4 — How is Text Stored?

ASCII decimal codes:
- Uppercase A = 65
- Lowercase a = 97

Why does a computer need an encoding standard?
Computers store text as numbers, so an encoding standard maps characters to numerical values. It ensures that text is stored, transmitted and interpreted consistently across different devices and systems

Example of a character outside basic ASCII:
- ₹ (Indian Rupee symbol)

Python function used:
- `ord()` — Returns the numerical code point of a character. For A and a, these values match their ASCII decimal codes.