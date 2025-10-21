# EX-05 Program to Check Whether the First Element of an Array is Divisible by 3

## AIM:
To write a C program that reads n elements into an array and checks whether the first element is divisible by 3.

## ALGORITHM:

1. Start
2. Declare an integer variable num.
3. Read the value of num (size of the array) from the user.
4. Declare an integer array arr[num].
5. Use a for loop from i = 0 to i < num:
    a. Read each element and store it in arr[i].
6. Check if the first element arr[0] is divisible by 3 using the condition:
    a. If arr[0] % 3 == 0, print "The first element is divisible by 3".
    b. Else, print "The first element is not divisible by 3".
7. Stop

## PROGRAM:
```
#include <stdio.h>

int main()
{
    int num;
    printf("Enter the size of the array: ");
    scanf("%d",&num);
    int arr[num];
    printf("Enter the elemnts of the array: ");
    for(int i = 0; i < num; i++)
    {
        scanf("%d",&arr[i]);
    }
    if(arr[0] % 3 == 0)
    {
        printf("The first element %d is divisible by 3",arr[0]);
    }
    else
    {
        printf("The first element %d is not divisible by 3",arr[0]);
    }
    return 0;
}
```

## OUTPUT:
<img width="676" height="146" alt="image" src="https://github.com/user-attachments/assets/483c568e-eabe-4967-846f-7e3197643df9" />

## RESULT:
The program successfully reads n elements from the user and checks whether the first element of the array is divisible by 3.
