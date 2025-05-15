# EX 20 C Program to compare two strings using strcmp()..
## AIM:
To write a Program to compare two strings using strcmp().
## Algorithm
1. Start
2. Declare two character arrays str1 and str2
3. Input the two strings from the user
4. Use the function strcmp(str1, str2) to compare them
5. If the result of strcmp() is:  
   a. 0 → The strings are equal  
   b. < 0 → str1 is less than str2 (lexicographically)  
   c. > 0 → str1 is greater than str2 (lexicographically)  
6. Display the appropriate result
7. End   

## Program:
```
#include<stdio.h>
int main()
{
    char str1[100],str2[100];
    scanf("%s",str1);
    scanf("%s",str2);
    int i=0;
    while(str1[i]==str2[i])
    {
        if(str1[i] == '\0')
        {
            printf("strings are same");
            return 0;
        }
        i++;
    }
    printf("strings are not same");
}
```

## Output:
![image](https://github.com/user-attachments/assets/7fa86f29-739b-4218-93d3-99eca9d4744b)


## Result:
Thus the program was executed and the output was verified successfully.
