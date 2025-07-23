AIM: To study and implement C++ Bitwise Operators

SOFTWARE REQUIRED:
Visual Studio

THEORY:
In C++, Bitwise Operators are the operators that are used to perform bit-level operations on the integers. While performing these operations, integers are considered as sequences of binary digits. These operators are useful for low-level programming, system programming, and optimizing performance.

Bitwise AND (&):
Bitwise AND operation compare each bit at the same position in the integer and the resultant bit will be set (1) only and only if both corresponding bits are set (1), otherwise it will be unset (0). The symbol which is used to perform bitwise AND operation is &.

Bitwise OR (|):
The Bitwise OR operation compares each bit at the same position, and the result bit will be set (1) if any of the corresponding bits are set (1). The symbol used to perform the bitwise OR operation is |.

Bitwise XOR (^):
The Bitwise XOR operation compares each bit at the same position, and the result bit will be set (1) if the corresponding bits differ, i.e., one should be 1 and the other should be 0. The symbol used to perform the bitwise XOR operation is ^.

Bitwise NOT (~):
The Bitwise NOT operation is performed on a single number. It changes the current bit to its complement, i.e., if the current bit is 0, then in the result it will be 1, and if the current bit is 1, it will become 0. It is denoted by the symbol ~.

Left Shift (<<):
The leftshift operator shifts the bits of an integer to the left by a specific number of positions (as mentioned). This left shift operation is equivalent to multiplying the integer by 2 raised to the power of the number of positions shifted. The symbol used to represent the left shift operator is <<.

Right Shift (>>):
The right shift operator shifts the bits of an integer to the right by a specific number of positions. This right shift operation is equivalent to dividing the integer by 2 raised to the power of the number of positions shifted. The symbol used to represent the right shift operator is >>.

IMPLEMENTATION:
The Bitwise Operators are used in the following cases which helps to understand the operators in C++.

Usage of Bitwise Operators(basic)
To set specific Bits(Uses Binary logic)
ALGORITHM:

Program 1 

Objective: To perform and display results of various bitwise operations using two predefined integers.

STEPS:
1.Start

2.Declare and initialize two integers:
a ← 4 b ← 2

3.perform bitwise operations:
bitwise_and ← a AND b (a & b)

bitwise_or ← a OR b (a | b)

bitwise_xor ← a XOR b (a ^ b)

bitwise_not ← NOT a (~a)

4.Perform shift operations:
leftshift ← a shifted left by 2 bits (a << 2)

rightshift ← 3 shifted right by a bits (3 >> a)

5.Display results:
Output all computed values to the console using cout

6.End

Program 2

Objective: To modify a predefined integer by setting and resetting specific bits as per user input.

STEPS:

1.Start

2.Initialize integer i ← 76

3.Ask the user to enter the bit position to set

4.Read input into bit_to_be_set

5.Set the specified bit using bitwise OR:
set ← i | (1 << bit_to_be_set)

6.Ask user to enter the bit position to reset

7.Read input into reset

8.Reset the specified bit using bitwise AND with bitwise NOT:
reset ← i & ~(1 << reset)

9.Display the result after setting

10.Display the result after resetting

11.End

CONCLUSION:
This Document as well as Program discovers the various types of bitwise operators that are available in C++.
