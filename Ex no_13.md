# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
Start.
Define a variables i,j,n,a.
Write program to find n x n matrix.
Read the value using scanf.
Ask the user to make an input
Print out the answer.
End.  

## Program:
```
#include<stdio.h> 
int main()
{
int i,j,n,a[10][10];
scanf("%d",&n); 
for(i=0;i<n;i++)
{
for(j=0;j<n;j++)
{
scanf("%d",&a[i][j]);
}
}for(i=0;i<n;i++)
{
for(j=0;j<=n;j++)
{
if(a[i][j]%2==1)
{
printf("a[%d][%d] is %d \n",i,j,a[i][j]);
}
}
printf("\n");
}
return 0;
}
```

## Output:
<img width="796" height="572" alt="image" src="https://github.com/user-attachments/assets/49a2b48d-ea18-4fe5-9253-1f607830d12c" />



## Result:
Thus the program was executed and the output was verified successfully.
