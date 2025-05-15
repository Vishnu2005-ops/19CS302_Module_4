# EX 18 C program to find the length of the string 'UMBRELLA'
## AIM:
To write a C program to find the length of the string 'UMBRELLA'
## Algorithm
1. Start
2.  a string str and initialize it with "UMBRELLA"
3. Initialize a counter variable length = 0
4. Traverse the string until the null character '\0' is found  
5. For each character, increment length by 1
6. After the loop ends, length contains the total number of character
7. Display the value of length
8. End 

## Program:
```
#include<stdio.h>
#include<string.h>
int main()
{
   char str[100];
   scanf("%s",str);
   int strlength = strlen(str);
   printf("Length of Str is %d",strlength);
}
```
## Output:

![image](https://github.com/user-attachments/assets/0b36d706-48f2-4e26-b4e4-a4d88f49c287)


## Result:
Thus the program was executed and the output was verified successfully.
