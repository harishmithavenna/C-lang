# Bit Wise Operators
-Basically It Performs Operations On Bits
-In C we Have Bitwise Operators that is very important in embedded systems 
## Why BItwise Operators are Important In Embedded Systems?
- To Set a Particular Bit
- To clear a Particular Bit
- To Toggle a Bit
- Hardware Registers are Bit-Oriented
- Efficient Memory Usage
- Fast Execution

## 6 bitwise operators
AND (&)                            Bitwise AND            Both Bits Must be in Set 
OR(|)                              Bitwise OR             Any one of the Bit Must be 1
Not(!)                             Bitwise Not            Complement
>>                                 Right Shift            Shifts bits to the right by a specified number of positions
<<                                 left shift             Shifts bits to the left by a specified number of position
^                                  Bitwise XOR            Sets a bit to 1 if the bits are different
## 
-Set, Clear, Toggle, and Check are not separate C operators.
-They are common bit manipulation operations performed using the bitwise operators.
-Set a Bit
-Meaning: Make a particular bit 1
-Syntax: num = num | (1 << Pos);
-clear a Bit
-Meaning: Make a particular bit 0
-Syntax: num = num &~ (1 << Pos);
-Toggle a Bit
-Meaning: Make a particular bit Complement
-Syntax: num = num ^ (1 << Pos);
- Check a Bit
-Meaning: Check a Bit is Set or clear
-Syntax: num = num & (1 << Pos);

## Difference Between the Logical Operators and Bitwise operator
- Logical Operators Gives Boolean Values as a Answer
- But Bitwise Operator Gives 0/1 as a Answer -- Works on Bits 

example
- Bitwise  7&2=  0111 & 0010 =0010
-Logical   7&&2= Both are non zero values so True (1)
