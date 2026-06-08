# EX 3 C program to find number of years based on principle, rate & simple interest.

## DATE:08/06/2026

## AIM:

To write a C program to find number of years based on principle, rate & simple interest.

## Algorithm

1. Start the program.

2. Declare variables for principal, rate, simple interest, and years.

3. Assign values to principal, rate, and simple interest.

4. Calculate the number of years using the formula:

   Years = (Simple Interest × 100) / (Principal × Rate)

5. Display the number of years.

6. Stop the program.

## Program:

```c id="h4u2vm"
#include <stdio.h>

int main()
{
    float principal = 1000, rate = 5, si = 250;
    float years;

    years = (si * 100) / (principal * rate);

    printf("Number of years = %.2f", years);

    return 0;
}
```

## Output:

```text id="r5q8yn"
Number of years = 5.00
```

## Result:

Thus the program was executed and the output was verified successfully.
