# EX 19 C program to copy a  string  into another string without using strcpy() ,and find the total number of words in a given strings using DO WHILE loop
## AIM:
To write a c program to copy a  string  into another string without using strcpy() ,and find the total number of words in a given strings using DO WHILE loop

## Algorithm
1. Start
2. Declare two character arrays str1[100] and str2[100]
3. Declare an integer variable count = 0
4. Input the first string str1 using scanf("%[^\n]", str1) (reads until newline)
5. Input the second string str2 using scanf("%s", str2) (reads a single word)
6. Use strcat(str1, str2) to concatenate str2 to the end of str1
7. Print the concatenated string
8. Initialize a loop with i = 0
9. Traverse str1 using a for loop:
10. For each character until null character '\0' is reached:
11. Increment count by 1
12. After loop ends, print the value of count
13. End

## Program:
```
#include<stdio.h>
#include<string.h>
int main()
{
    char str1[100],str2[100];
    int count = 0;
    scanf("%[^\n]",str1);
    scanf("%s",str2);
    
    strcat(str1,str2);
    printf("s2:%s\n",str1);
    
    for(int i=0;str1[i]!=0;i++)
    {
        count = count + 1;
    }
    printf("Total words: = %d",count);
}
```

## Output:

![image](https://github.com/user-attachments/assets/d459636e-6eac-4da8-9e49-40da7ddd38f8)


## Result:
Thus the program was executed and the output was verified successfully.
