//# c-29
//no argument and with return values
#include<stdio.h>
int number()
{
    return 99;
}
int main()
{
   int n=number();
   printf("the number from sub function is %d \n",n);
    return 0;
}
