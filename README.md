# Exam Notes

## Number Systems and Bases
- Base: The number of digits a counting system uses. For example, the decimal system has a base of 10 (digits 0-9).
- Binary: Base 2 system with digits 0 and 1, used in electronic systems.

## Place Values
- Decimal: Each place value is a power of 10. For example, in 7345, the place value of 3 is 300.
- Binary: Each place value is a power of 2. For example, in 1011, the place value of the leftmost 1 is 8.

## Conversions

- Binary to Decimal: Calculate the place value of each digit and add them.
- Decimal to Binary: Divide by 2 and track the remainders.
- Hexadecimal: Base 16 system with digits 0-9 and A-F. Compact representation for binary numbers.
- Hexadecimal to Decimal: Calculate the place value of each digit and add them.
- Decimal to Hexadecimal: Divide by 16 and track the remainders.

## Hexadecimal Colors
- Represented by a hash (#) followed by 6 hex digits (e.g., #1F256A). Convert to RGB format.

## Bit Shifting
- Right Shift: Drop the right-most digits.
- Left Shift: Add zeros to the end.

## Conversion Between Bases
Convert to decimal first, then to the target base.

## Truth Tables

### AND
| p | q | p & q |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | F     |
| F | F | F     |

### OR

| p | q | p V q |
|---|---|-------|
| T | T | T     |
| T | F | T     |
| F | T | T     |
| F | F | F     |

### XOR

| p | q | p ^ q |
|---|---|-------|
| T | T | F     |
| T | F | T     |
| F | T | T     |
| F | F | F     |

### =>

| p | q | p => q |
|---|---|---------|
| T | T | T      |
| T | F | F      |
| F | T | T      |
| F | F | T      |

### <=>

| p | q | p <=> q |
|---|---|----------|
| T | T | T       |
| T | F | F     |
| F | T | F       |
| F | F | T       |

## Bitwise Operations

### Common Bitwise Operations
- AND (&): Compares each bit of two numbers and returns a new number where each bit is 1 only if both compared bits are 1.
    - Example: 5 & 3 (in binary: 0101 & 0011 = 0001 which is 1 in decimal)
- OR (|): Compares each bit of two numbers and returns a new number where each bit is 1 if at least one of the compared bits is 1.
    - Example: 5 | 3 (in binary: 0101 | 0011 = 0111 which is 7 in decimal)
- XOR (^): Compares each bit of two numbers and returns a new number where each bit is 1 if the compared bits are different.
    - Example: 5 ^ 3 (in binary: 0101 ^ 0011 = 0110 which is 6 in decimal)
- NOT (~): Flips each bit of a number, turning 1s into 0s and 0s into 1s.
    - Example: ~5 (in binary: ~0101 = 1010 which is -6 in decimal due to two’s complement representation)
- Left Shift (<<): Shifts all bits of a number to the left by a specified number of positions, adding zeros on the right.
    - Example: 5 << 1 (in binary: 0101 << 1 = 1010 which is 10 in decimal)
- Right Shift (>>): Shifts all bits of a number to the right by a specified number of positions, dropping bits on the right.
    - Example: 5 >> 1 (in binary: 0101 >> 1 = 0010 which is 2 in decimal)

## Sets

A set is a well-deﬁned collection of distinct objects
Represented using capital letters (S, A, B, U)
The objects are called elements/members
No duplicates in sets

### Examples:
- A = {1, 10, 12, 15}
- B = {5, 99, 2, 67, 12} = {2, 5, 12, 67, 99}
- C = {} or Φ (phi - greek) or ∅ (miniscule -
Danish/Norwegian)

Universal set “U” is a set which consists of all the
elements of the relevant
sets.
A = {1, 2, 3, 4, 5}
B = {3, 4, a, b, c}
U = {1, 2, 3, 4, 5, a, b, c}

### Union 
The union of sets refers to the combination of all elements from the sets

A u B = {x : x ∈ A or x ∈ B}

##### Example: 

A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

A u B = {1, 2, 3, 4, 5, 6}

### Intersection

The intersection of sets refers to the elements that are present in both sets

A ∩ B = {x : x ∈ A and x ∈ B}

#### Example:

A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

A ∩ B = {3, 4}

### Relative Complement

The relative complement of sets refers to the elements that are present in the first set but not in the second set

A - B = {x : x ∈ A and x ∉ B}

#### Example:

A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

A - B = {1, 2}

### Complement

The complement of sets refers to the elements that are not present in the set

A' = U - A = {x : x ∈ U and x ∉ A}

#### Example:

U = {1, 2, 3, 4, 5, 6}
A = {3, 6}

A' = U - A = {1, 2, 4, 5}

