# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## DATE:08/06/2026

## AIM:

To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm

1. Start the program.
2. Declare an integer variable for age.
3. Read the age from the user.
4. Check whether the age is greater than or equal to 21 using an `if` statement.
5. If the condition is true, display "Eligible for Marriage".
6. Stop the program.

## Program:

```c id="x4m8kp"
#include <stdio.h>

int main()
{
    int age;

    printf("Enter age: ");
    scanf("%d", &age);

    if (age >= 21)
    {
        printf("Eligible for Marriage");
    }

    return 0;
}
```

## Output:

```text id="y7n2qw"
Enter age: 25
Eligible for Marriage
```

## Result:

Thus the program was executed and the output was verified successfully.
