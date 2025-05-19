# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE: 19/05/25
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output

## Program:
```
/*
Program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
Developed by: 
RegisterNumber:  
*/
```

#include <stdio.h>

int main() {
    int marks[7];
    int i, total = 0;
    float average, percentage;
    for (i = 0; i < 7; i++) {
        printf("Subject %d: ", i + 1);
        scanf("%d", &marks[i]);
        total += marks[i];
    }

    average = total / 7.0;
    percentage = (total / (7.0 * 100)) * 100;  // Assuming each subject is out of 100

    printf("\nTotal Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average);
    printf("Percentage = %.2f%%\n", percentage);

    return 0;
}

## Output:

Total Marks = 590
Average Marks = 84.29
Percentage = 84.29%

## Result:
Thus the program was executed and the output was verified successfully.
