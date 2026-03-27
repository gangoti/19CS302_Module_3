# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.
## DATE:
## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
Start
Declare the variable i.
Read the value given using scanf.
Check whether the given number is prime or not using if-else statement condition.
If true,print ("%d is a prime number.",i).
If false, print ("%d is not a prime number.",i).
End.
   

## Program:
```
int main()
{
int i; 
scanf("%d",&i);
if(i%2==1 && i%1==0)
{
printf("%d is a prime number.",i);
}
else
{
printf("%d is not a prime number.",i);
}
return 0;
}
```

## Output:
<img width="682" height="233" alt="image" src="https://github.com/user-attachments/assets/8c09ea9f-eef1-4e9a-888d-24adfc3bc302" />


## Result:
Thus the program was executed and the output was verified successfully.
