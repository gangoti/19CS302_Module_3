# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
 Start.
Declare a array size value of type int.
Prompt the user to enter a value.
Read the value using scanf.
Initialize array elements.
Replace all even elements to E
End.

## Program:
```
c program
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
```

## Output:
<img width="464" height="177" alt="image" src="https://github.com/user-attachments/assets/b7ea9097-af93-4f73-8208-fe17f5dd63e8" />


## Result:
Thus the program was executed and the output was verified successfully.
