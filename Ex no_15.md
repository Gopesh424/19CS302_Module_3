# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:07/05/2025
## AIM:To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start. 
2. Declare a array size value of type int. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Initialize array elements. 
6. Replace all even elements to E 
7. End. 

## Program:
```
#include <stdio.h> 
int main() { 
    int arr[100], n; 
    scanf("%d", &n); 
    for (int i = 0; i < n; i++) { 
        scanf("%d", &arr[i]); 
    } 
    for (int i = 0; i < n; i++) { 
        if (arr[i] % 2 == 0) 
            printf("E "); 
        else 
            printf("%d ", arr[i]); 
    } 
    printf("\n"); 
    return 0; 
} 
/*
Program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
Developed by: 
RegisterNumber:  
*/
```

## Output:
5
2 3 4 5 6
E 3 E 5 E


## Result:
Thus the program was executed and the output was verified successfully.
