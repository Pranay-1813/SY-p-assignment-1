#include<stdio.h>
int main()
{
     char operators;
     int a,b;
     

     printf("Enter the  operators(+,-,*,/):");
     scanf("%c",&operators);

     printf("Enter the two numbers:");
     scanf("%d %d",&a,&b);

     switch(operators)
     {
       case '+':
       printf("%d+%d=%d",a,b,a+b); 
       break;
       
       case '-':
       printf("%d-%d=%d",a,b,a-b);
       break;

       case '*':
       printf("%d*%d=%d",a,b,a*b);
       break;
       
       case '/':
       printf("%d/%d=%d",a,b,a/b);
       break;
       }
      
       return 0;
  }
  
