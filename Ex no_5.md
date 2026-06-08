# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:08/06/2026
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. Start the program.
2. Input marks of seven subjects.
3. Calculate the total marks by adding all seven subject marks.
4. Calculate the average as Total / 7 and percentage as (Total / 700) × 100 (assuming each subject is out of 100).
5. Display the total, average, and percentage, then stop the program.
 

## Program:
```
#include <stdio.h>

int main()
{
    float s1, s2, s3, s4, s5, s6, s7;
    float total, average, percentage;

    printf("Enter marks of 7 subjects:\n");
    scanf("%f %f %f %f %f %f %f", &s1, &s2, &s3, &s4, &s5, &s6, &s7);

    total = s1 + s2 + s3 + s4 + s5 + s6 + s7;
    average = total / 7;
    percentage = (total / 700) * 100;

    printf("Total Marks = %.2f\n", total);
    printf("Average = %.2f\n", average);
    printf("Percentage = %.2f%%\n", percentage);

    return 0;
}
Developed by: Manimaran B
RegisterNumber:  212223060148

```

## Output:
<img width="413" height="416" alt="image" src="https://github.com/user-attachments/assets/9cdf9d88-157e-42fa-9f2e-fa8704326e07" />



## Result:
Thus the program was executed and the output was verified successfully.
