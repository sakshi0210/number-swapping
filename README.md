# number-swapping
it has swapping the numbers  .c program

#include<stdio.h>
#include<conio.h>
main()
{int a;
int b;

printf("Enter number a=");
scanf("%d",&a);
printf("Enter number b=");

scanf("%d",&b);
printf("You want a=%d and b=%d .",a,b);
b=a+b;
a=b-a;
b=b-a;
printf("Value of a and b after swapping is a=%d and b=%d .",a,b);
return 0;
}
