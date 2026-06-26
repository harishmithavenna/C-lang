## Size and Range of the Data Types
                                                         Data types 
                                                              |
                                                              |
-Basic Data Types                                      - Derived Data Types                         -User Defined data types
- Char - 1 Byte                                        - Arrays                                     -Unions
-Range of UnSigned Char - 0 to 255                     - Pointers                                   -typedef                                                      
-Range of UnSigned Char - -128 to 127                  - Functions                                  -Struct
- Int - 4 Byte                                                                                      -enum
-Range of UnSigned int  - 0 to 4,294,967,295
-Range of Signed  - -2,147,483,648 to 2,147,483,647
-Double - 8 Bytes
-Float - 4 Bytes
 
#Example:                                          # Important Points to remember while the programming  

-problem                                          - Size of the data type
-char data types:                                 - if the type is not defined like signed or unsigned compiler automatically takes signed as a data type
                                                  - Here char ch= 150  that is signed                                               
#include<stdio.h>                                 - so range of signed char is -128 to 127
int main(){                                       - By the problem we have it is out of range                                 
char ch=150;                                      - so we need to out of range 
printf("%d\n",ch);|                            
}                                            internally char =1 byte = 8 bits
                                   128  64  32  16    8  4  2  1
                                    1    0   0   1    0  1  1  0
                                 - when MSB=1 it is negative value so we need do 2's Complement
                                 - when MSB=0 it is Positive
finally we got answer ch=- 106
