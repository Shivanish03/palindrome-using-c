/*# palindrome-using-c
/*checking palindrome for integers
#include<stdio.h>
#include<conio.h>
int main()
{
/* n= digit user provide as input for checking and r = remainder  
int n,r=0;
/* program will continue if the n is not equal to 0 
while(n!=0)
printf("enter the values:-");
scanf("%d", n);
r=n%10; 
/*for printing last digit 
r=r*10; 
/*for getting exact digit 
n=n%10;
/* for printing first two digits
}
if(n==r)
printf("yes given series is a palindrome series");
else
printf("the given series is not a palindrome series ");
return 0;
