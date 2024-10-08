# Python Operators Notes

## 1. Arithmetic Operators

Arithmetic operators are used to perform mathematical operations.

| Operator | Description                        | Example          | Output  |
|----------|------------------------------------|------------------|---------|
| `+`      | Addition                           | `5 + 3`          | `8`     |
| `-`      | Subtraction                        | `5 - 3`          | `2`     |
| `*`      | Multiplication                     | `5 * 3`          | `15`    |
| `/`      | Division                           | `5 / 2`          | `2.5`   |
| `//`     | Floor Division                     | `5 // 2`         | `2`     |
| `%`      | Modulus (Remainder)               | `5 % 2`          | `1`     |
| `**`     | Exponentiation                     | `2 ** 3`         | `8`     |

## 2. Comparison Operators

Comparison operators are used to compare two values.

| Operator | Description                        | Example          | Output   |
|----------|------------------------------------|------------------|----------|
| `==`     | Equal to                           | `5 == 5`         | `True`   |
| `!=`     | Not equal to                       | `5 != 3`         | `True`   |
| `>`      | Greater than                       | `5 > 3`          | `True`   |
| `<`      | Less than                          | `5 < 3`          | `False`  |
| `>=`     | Greater than or equal to          | `5 >= 5`         | `True`   |
| `<=`     | Less than or equal to             | `5 <= 3`         | `False`  |

## 3. Logical Operators

Logical operators are used to combine conditional statements.

| Operator | Description                        | Example                | Output   |
|----------|------------------------------------|------------------------|----------|
| `and`    | Logical AND                       | `True and False`       | `False`  |
| `or`     | Logical OR                        | `True or False`        | `True`   |
| `not`    | Logical NOT                       | `not True`             | `False`  |

## 4. Bitwise Operators

Bitwise operators perform operations on bits and are commonly used in low-level programming.

| Operator | Description                        | Example          | Output    |
|----------|------------------------------------|------------------|-----------|
| `&`      | Bitwise AND                       | `5 & 3`          | `1`       |
| `|`      | Bitwise OR                        | `5 | 3`          | `7`       |
| `^`      | Bitwise XOR                       | `5 ^ 3`          | `6`       |
| `~`      | Bitwise NOT                      | `~5`             | `-6`      |
| `<<`     | Left shift                        | `5 << 1`         | `10`      |
| `>>`     | Right shift                       | `5 >> 1`         | `2`       |

## 5. Assignment Operators

Assignment operators assign values to variables.

| Operator | Description                        | Example          | Equivalent  |
|----------|------------------------------------|------------------|-------------|
| `=`      | Assigns a value                   | `x = 5`          | -           |
| `+=`     | Add and assign                    | `x += 3`         | `x = x + 3` |
| `-=`     | Subtract and assign               | `x -= 3`         | `x = x - 3` |
| `*=`     | Multiply and assign               | `x *= 3`         | `x = x * 3` |
| `/=`     | Divide and assign                 | `x /= 3`         | `x = x / 3` |
| `//=`    | Floor divide and assign           | `x //= 3`        | `x = x // 3`|
| `%=`     | Modulus and assign                | `x %= 3`         | `x = x % 3` |
| `**=`    | Exponentiate and assign           | `x **= 3`        | `x = x ** 3`|
| `&=`     | Bitwise AND and assign            | `x &= 3`         | `x = x & 3` |
| `|=`     | Bitwise OR and assign             | `x |= 3`         | `x = x | 3` |
| `^=`     | Bitwise XOR and assign            | `x ^= 3`         | `x = x ^ 3` |
| `<<=`    | Left shift and assign             | `x <<= 3`        | `x = x << 3`|
| `>>=`    | Right shift and assign            | `x >>= 3`        | `x = x >> 3`|

## 6. Identity Operators

Identity operators are used to compare the memory locations of two objects.

| Operator | Description                        | Example             | Output  |
|----------|------------------------------------|---------------------|---------|
| `is`     | Checks if two variables refer to the same object | `x is y`       | `True/False` |
| `is not` | Checks if two variables do not refer to the same object | `x is not y` | `True/False` |

## 7. Membership Operators

Membership operators are used to test whether a value is found in a sequence (like strings, lists, or tuples).

| Operator | Description                        | Example             | Output  |
|----------|------------------------------------|---------------------|---------|
| `in`     | Checks if a value is in a sequence | `5 in [1, 2, 3, 5]` | `True`  |
| `not in` | Checks if a value is not in a sequence | `5 not in [1, 2, 3]` | `True` |

## Summary

- **Arithmetic operators** perform basic mathematical operations.
- **Comparison operators** compare values.
- **Logical operators** combine conditional statements.
- **Bitwise operators** operate on the bits of integers.
- **Assignment operators** assign values to variables.
- **Identity operators** compare memory locations.
- **Membership operators** check for membership within sequences.


