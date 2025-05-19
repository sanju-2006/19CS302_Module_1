# EX 2 C program to check whether the attendance is PRESENT using simple if statement.
## DATE: 19/05/25
## AIM:
To write a program to check whether the attendance is PRESENT using simple if statement.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output
6. 
## Program:
```
/*
Program to check whether the attendance is PRESENT using simple if statement.
Developed by: 
RegisterNumber:  
*/


#include <stdio.h>
#include <string.h>

int main() {
    char attendance[10];
    scanf("%s", attendance);
    
    if (strcmp(attendance, "PRESENT") == 0) {
        printf("The student is PRESENT.\n");
    }

    return 0;
}


## Output:
The student is PRESENT.



## Result:
Thus the program was executed and the output was verified successfully.
