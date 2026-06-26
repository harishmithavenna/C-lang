# Operators 
## What is Operators? 
-Operators= Operator+operand
-Example
a=10+20;
-Here 10,20 is Operands
-+ is Operator
## Uses of the Operator
- It is used to PErform ALU operations in CPU
## Types of Operators
- Unary Operator -------- Incrementation ,decrementation,complement(++a,a--)
- Binary Operator----------Arithmetic Operator,Relational,Logical(a=10+20,c=3*3)
- Ternary Operator---------Conditional Operators

## Operator Precedence & Associativity in C

+--------------------------------------+-------------------------------+------------------+
| OPERATOR                             | TYPE                          | ASSOCIATIVITY    |
+--------------------------------------+-------------------------------+------------------+
| ()   []   .   ->                    | Postfix Operator             | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| ++  --  +  -  !  ~  (type)  *  &    | Unary Operator              | right-to-left    |
| sizeof                              |                               |                  |
+--------------------------------------+-------------------------------+------------------+
| *   /   %                           | Arithmetic Operator         | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| +   -                               | Arithmetic Operator         | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| <<   >>                             | Shift Operator              | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| <   <=   >   >=                     | Relational Operator         | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| ==   !=                             | Equality Operator           | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| &                                   | Bitwise AND Operator        | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| ^                                   | Bitwise EX-OR Operator      | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| |                                   | Bitwise OR Operator         | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| &&                                  | Logical AND Operator        | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| ||                                  | Logical OR Operator         | left-to-right    |
+--------------------------------------+-------------------------------+------------------+
| ?:                                  | Ternary Conditional Operator| right-to-left    |
+--------------------------------------+-------------------------------+------------------+
| =  +=  -=  *=  /=  %=  &=  ^=       | Assignment Operator         | right-to-left    |
| |=  <<=  >>=                        |                               |                  |
+--------------------------------------+-------------------------------+------------------+
| ,                                   | Comma Operator              | left-to-right    |
+--------------------------------------+-------------------------------+------------------+

-Example Program
#include<stdio.h>
int main(){                       - output explanation 
int x = 20 / 5 * 2;                 20 / 5 = 4  
printf("%d",x);                     4 * 2 = 8
}                        final answer = 8
