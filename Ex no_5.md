# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## DATE:08/06/2026

## AIM:

To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm

1. Start the program.
2. Declare variables for seven subject marks, total, average, and percentage.
3. Read the marks of the seven subjects.
4. Calculate the total marks.
5. Calculate the average marks.
6. Calculate the percentage.
7. Display the total, average, and percentage.
8. Stop the program.

## Program:

```c id="m7q2vk"
#include <stdio.h>

int main()
{
    float s1, s2, s3, s4, s5, s6, s7;
    float total, average, percentage;

    printf("Enter marks of 7 subjects: ");
    scanf("%f %f %f %f %f %f %f",
          &s1, &s2, &s3, &s4, &s5, &s6, &s7);

    total = s1 + s2 + s3 + s4 + s5 + s6 + s7;
    average = total / 7;
    percentage = (total / 700) * 100;

    printf("Total = %.2f\n", total);
    printf("Average = %.2f\n", average);
    printf("Percentage = %.2f%%", percentage);

    return 0;
}
```

## Output:

```text id="n8w4rp"
Enter marks of 7 subjects: 80 85 90 75 88 92 78
Total = 588.00
Average = 84.00
Percentage = 84.00%
```

## Result:

Thus the program was executed and the output was verified successfully.
