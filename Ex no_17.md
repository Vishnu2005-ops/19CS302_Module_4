# EX 17  C program to check even or odd number using bitwise operator using if else
## AIM:
To write a C program to check even or odd number using bitwise operator using if else
## Algorithm
1. Start
2. Input an integer number num
3. Perform bitwise AND operation: result = num & 1
4. If result == 1, then  
   a. Print "num is Odd"  
5. Else  
   a. Print "num is Even"  
6. End

## Program:
```
#include <stdio.h>
int main() {
    int number;
        scanf("%d", &number);
    if (number & 1) {
        printf("%d is odd.\n", number);
    } else {
        printf("%d is even.\n", number);
    }
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/f8d1dc6b-0ec5-4c08-9cd1-863aeaab0751)


## Result:
Thus the program was executed and the output was verified successfully.
