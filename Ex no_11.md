# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
Start.
Declare a integer variable
Define a function named dectobin.
Return the integer.
Read the value using scanf.
Convert decimal to binary value.
Print the dectobin
End.  

## Program:
```
#include<stdio.h>
Int dectobin(int d){
int bin =0,base=1,rem; 
while(d>0)
{
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10;
}
printf(" = %d in binary",bin); 
return 0;
}
int main()
{
int dec; 
scanf("%d",&dec);
printf("%d in decimal",dec); 
dectobin(dec);
return 0;
```

## Output:
<img width="769" height="282" alt="image" src="https://github.com/user-attachments/assets/dc8ea0e5-a9e7-40c4-b351-53534099bbe0" />


## Result:
Thus the program was executed and the output was verified successfully.
