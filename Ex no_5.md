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

#include <stdio.h>

int main() {
    int marks[7];
    int i, total = 0;
    float average, percentage;

    // Reading marks for 7 subjects
    printf("Enter marks for 7 subjects:\n");
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
Enter marks for 7 subjects:
Subject 1: 78
Subject 2: 85
Subject 3: 90
Subject 4: 82
Subject 5: 76
Subject 6: 88
Subject 7: 91

Total Marks = 590
Average Marks = 84.29
Percentage = 84.29%



## Result:
Thus the program was executed and the output was verified successfully.
