# EX1(C) Implementation of Tower of Hanoi
## DATE:26-03-2025
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1.Start the program.

2.Include the required libraries.

3.Define a recursive function to handle the tower of hanoi problem.

4.Call the defined function in the main function and print the moves.

5.End the program. 

## Program:
```
/*
Program to implement Tower of Hanoi
Developed by: BHUVANESHWARI M
RegisterNumber:  212223230033
*/

#include<stdio.h>
void TOH(int n,char x,char y,char z)
{
  if ( n>0)
  {
      TOH(n-1,x,z,y);
      printf("%c to %c\n", x,y);
      TOH(n-1, z,y,x);
  }
  
}
int main()
{
    
    int n= 3;
    scanf("%d", &n);
    TOH(n ,'A', 'B' , 'C');
}
```

## Output:
![image](https://github.com/user-attachments/assets/1f7270f7-ec3e-479b-ba9d-6154912d5211)



## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
