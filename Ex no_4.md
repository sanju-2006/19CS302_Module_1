# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE: 19/05/25
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output

## Program:
```
/*
Program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>

int main() {
    int age;
    scanf("%d", &age);

    if (age >= 21) {
        printf("Eligible for marriage.\n");
    } else {
        printf("Not eligible for marriage.\n");
    }

    return 0;
}


## Output:

Eligible for marriage.



## Result:
Thus the program was executed and the output was verified successfully.
