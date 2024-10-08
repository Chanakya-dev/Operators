# Bit Conversions and Bitwise Operators in Python

## Bit Conversions

### What is Bit Conversion?

Bit conversion refers to changing the representation of numbers between different bases, particularly between decimal (base 10) and binary (base 2). In binary, each digit represents a power of 2, and the positions of the digits correspond to increasing powers from right to left.

### Converting Decimal to Binary

To convert a decimal number to binary, follow these steps:

1. **Divide the number by 2**.
2. **Record the remainder** (0 or 1).
3. **Use the quotient for the next division**.
4. Repeat the process until the quotient is 0.
5. **Read the remainders from bottom to top**.

#### Example: Convert 13 to Binary

1. 13 ÷ 2 = 6, remainder **1**
2. 6 ÷ 2 = 3, remainder **0**
3. 3 ÷ 2 = 1, remainder **1**
4. 1 ÷ 2 = 0, remainder **1**

Reading the remainders from bottom to top: **1101**.  
Thus, **13 in decimal is 1101 in binary**.

### Converting Binary to Decimal

To convert a binary number to decimal:

1. **Identify the binary digits**.
2. **Multiply each digit by its corresponding power of 2** (starting from the right, where the rightmost digit is \(2^0\)).
3. **Sum all the results**.

#### Example: Convert 1101 to Decimal

- \(1 \times 2^3 = 1 \times 8 = 8\)
- \(1 \times 2^2 = 1 \times 4 = 4\)
- \(0 \times 2^1 = 0 \times 2 = 0\)
- \(1 \times 2^0 = 1 \times 1 = 1\)

**Sum: 8 + 4 + 0 + 1 = 13**.  
Thus, **1101 in binary is 13 in decimal**.

## Bitwise Operators

### 1. Bitwise AND (`&`)

The bitwise AND operator compares each bit of two numbers. If both bits are 1, the result is 1; otherwise, it is 0.

#### Example:

```python
a = 5  # (binary: 0101)
b = 3  # (binary: 0011)

result = a & b  # (binary: 0001) => decimal: 1
print(result)  # Output: 1
```
### 2. Bitwise OR (`|`)

The bitwise AND operator compares each bit of two numbers. If any one bits are 1, the result is 1; otherwise, it is 0.

#### Example:

```python
a = 5  # (binary: 0101)
b = 3  # (binary: 0011)

result = a & b  # (binary: 0111) => decimal: 1
print(result)  # Output: 7
```
