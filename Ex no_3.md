# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:08/06/2026
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Start the program.
2. Input the values of Principal (P), Rate of Interest (R), and Simple Interest (SI).
3. Calculate the number of years using the formula:
   
   Years = (SI × 100) / (P × R)

4. Display the calculated number of years.
5. Stop the program.


## Program:
```
#include <stdio.h> 
#include <math.h> 
int main() 
{ 
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r); 
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n)); 
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci); 
return 0; 
}
Developed by: Manimaran B 
RegisterNumber: 212223060148

```

## Output:

<img width="852" height="247" alt="image" src="https://github.com/user-attachments/assets/86e1cf13-f0b7-442b-95d5-4cca17e0a55a" />

## Result:
Thus the program was executed and the output was verified successfully.
