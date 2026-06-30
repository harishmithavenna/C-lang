# Strings
- String is a Collection of Characters which is end with ** \0 **
-example
char s[20]="hello";
- printf("%ld",sizeof(s)); // We got 6 as a size because it end's with ** \0 **
- C doesn't have String Data type 
-Where we use this Strings?
- In Email Logins and Passwords

## How to scan String
- to Scan String we use %s as a Format Specifier
- %s always need address
-Here name of the array itself is the address of the element

Example
-char s[20];
-printf("enter the string");
-scanf("%s",s);

## What \0 represents in String?
- it Is the end of the String 
- it represents Seperate between Valid and Invalid Characters
- it need 1 byte of data
- \0 is not visible when we are printing the string
- in size of string includes \0 also

