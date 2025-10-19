# Ptogram-3-c
## C-Module 3
## EX_NO-03)c)-ARRAY
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a program in C to read n number of values in an array and display it in reverse order.
## ALGORITHM:
1. Start the program.
2. Declare an integer variable n to store the size of the array.
3. Read the value of n from the user using scanf.
4. Declare an integer array of size n.
5. Use a for loop from 0 to n-1 to read n elements into the array using scanf.
6. Use another for loop from n-1 down to 0 to print the elements of the array in reverse order.
7. End the program.
## PROGRAM:
```
#include <stdio.h>

int main()
{
    int n, i;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
}
    for(i=n-1;i>=0;i--)    
        printf("%d ",a[i]);

    return 0;
}
```
## OUTPUT:
<img width="845" height="430" alt="Screenshot 2025-10-19 222108" src="https://github.com/user-attachments/assets/6aae3495-0431-4a2e-bd0e-6ae15394112b" />

## RESULT:
Thus the program to read n number of values in an array and display it in reverse order has been executed successfully
