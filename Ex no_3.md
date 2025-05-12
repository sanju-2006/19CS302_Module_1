# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1.Read inputs: Accept floating-point values for p, r, and s using scanf().
2.Compute years: Calculate n using n = (s * 100) / (p * r).
3.Format output: Display n with two decimal places using printf().
4.Ensure precision: Use %.2f to format the output neatly.
5.Terminate program: Complete execution and return from main().

## Program:
```
/*
Program to find number of years based on principle,rate & simple interest.
Developed by: santhiya c
RegisterNumber:212223060247  
*/
# include<stdio.h>
# include<math.h>
int main()
{
    float p,n,r,s;
    scanf("%f %f %f",&p,&r,&s);
    n=(s*100)/(p*r);
    printf("No.of.Year is = %.2f",n);
}
```

## Output:
![image](https://github.com/user-attachments/assets/9fa6e5ca-74fc-4ef8-ab4a-ecda9de4e45d)



## Result:
Thus the program was executed and the output was verified successfully.
