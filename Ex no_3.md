# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE: 19/05/25
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output

## Program:
```
/*
Program to find number of years based on principle,rate & simple interest.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
int main() {
    float principal, rate, simple_interest, time;
    printf("Enter Principal amount: ");
    scanf("%f", &principal);
    printf("Enter Rate of interest: ");
    scanf("%f", &rate);
    printf("Enter Simple Interest: ");
    scanf("%f", &simple_interest);

    // Calculate time (years)
    time = (simple_interest * 100) / (principal * rate);

    printf("Number of years = %.2f\n", time);

    return 0;
}


## Output:
Enter Principal amount: 1000
Enter Rate of interest: 5
Enter Simple Interest: 250
Number of years = 5.00


## Result:
Thus the program was executed and the output was verified successfully.
