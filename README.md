# C++ Bitwise Operators

This repository contains examples and explanations of bitwise operators in C++. Bitwise operators are used to manipulate individual bits within data. This README provides an overview of commonly used bitwise operators in C++ and how to use them.

## Table of Contents
- [Bitwise Operators](#bitwise-operators)
  - [Bitwise AND `&`](#bitwise-and-)
  - [Bitwise OR `|`](#bitwise-or-)
  - [Bitwise XOR `^`](#bitwise-xor-)
  - [Bitwise NOT `~`](#bitwise-not-)
  - [Left Shift `<<`](#left-shift-)
  - [Right Shift `>>`](#right-shift-)
- [Algorithm](#alorithm)

## Bitwise Operators

### Bitwise AND `&`

The bitwise AND operator `&` performs a bitwise AND operation between corresponding bits of two integers. It sets each bit of the result to 1 if both corresponding bits of the operands are 1.

### Bitwise OR `|`

The bitwise OR operator `|` performs a bitwise OR operation between corresponding bits of two integers. It sets each bit of the result to 1 if at least one of the corresponding bits of the operands is 1.

### Bitwise XOR `^`

The bitwise XOR (exclusive OR) operator `^` performs a bitwise XOR operation between corresponding bits of two integers. It sets each bit of the result to 1 if exactly one of the corresponding bits of the operands is 1.

### Bitwise NOT `~`

The bitwise NOT operator `~` inverts the bits of an integer. It changes each 0 to 1 and each 1 to 0.

### Left Shift `<<`

The left shift operator `<<` shifts the bits of an integer to the left by a specified number of positions. This effectively multiplies the integer by 2 raised to the power of the specified number.

### Right Shift `>>`

The right shift operator `>>` shifts the bits of an integer to the right by a specified number of positions. This effectively divides the integer by 2 raised to the power of the specified number.


## ALGORITHM**
### Set and Resst the given bit

### Set Bit Algorithm:

1.Start

2.Declare an integer variable (e.g., num) where you want to set a bit.

3.Declare an integer value (e.g., bitPosition) indicating the bit position you want to set (0-based index).

4.Use the bitwise OR operator | to set the bit:

5.Set num = num | (1 << bitPosition).

6.The specified bit is now set in the variable num.

7.End

### Reset (Clear) Bit Algorithm:
1.Start

2.Declare an integer variable (e.g., num) where you want to reset (clear) a bit.

3.Declare an integer value (e.g., bitPosition) indicating the bit position you want to reset (0-based index).

4.Use the bitwise AND operator & with the bitwise NOT operator ~ to reset the bit:

Set num = num & ~(1 << bitPosition).

5.The specified bit is now reset (cleared) in the variable num.

6.End

### Left Shift Algorithm:
1.Start

2.Declare an integer variable (e.g., num) that you want to left-shift.

3.Declare an integer value (e.g., shiftAmount) indicating the number of positions to left-shift num.

4.Use the left-shift operator << to perform the left shift:

Set num = num << shiftAmount.

5.The variable num will now contain the result of left-shifting by shiftAmount positions.

6.End

### Right Shift Algorithm:
1.Start

2.Declare an integer variable (e.g., num) that you want to right-shift.

3.Declare an integer value (e.g., shiftAmount) indicating the number of positions to right-shift num.

4.Use the right-shift operator >> to perform the right shift:

Set num = num >> shiftAmount.

5.The variable num will now contain the result of right-shifting by shiftAmount positions.

6.End

### Bit to be set or reset
### Set Bit Based on User Input Algorithm:

1.Start

2.Declare an integer variable (e.g., num) where you want to set a bit.

3.Prompt the user to enter the bit position they want to set (0-based index) and store it in an integer variable (e.g., bitPosition).

4.Use the bitwise OR operator | to set the bit:

Set num = num | (1 << bitPosition).

5.The specified bit is now set in the variable num.

6.End

### Reset (Clear) Bit Based on User Input Algorithm:

1.Start

2.Declare an integer variable (e.g., num) where you want to reset (clear) a bit.

3.Prompt the user to enter the bit position they want to reset (0-based index) and store it in an integer variable (e.g., bitPosition).

4.Use the bitwise AND operator & with the bitwise NOT operator ~ to reset the bit:

Set num = num & ~(1 << bitPosition).

5.The specified bit is now reset (cleared) in the variable num.

6.End

## OUTPUT
### Set and Reset the given bit
exp4_3
![image](https://github.com/Pranav18062004/Cpp-Bitwise-Operators/assets/79793482/79ccf7fa-21c1-459e-9479-9b913cd29616)

### Left Shift AND Right Shift
exp4_1
![image](https://github.com/Pranav18062004/Cpp-Bitwise-Operators/assets/79793482/ce7f5395-e199-4da3-8ca4-1f9b9a46292e)

### Bit to be set or reset
exp4_2
![image](https://github.com/Pranav18062004/Cpp-Bitwise-Operators/assets/79793482/dcbcc71d-1d3a-42db-8c44-8d5b6218ccfb)
