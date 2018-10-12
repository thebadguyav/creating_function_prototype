#include<stdio.h>
void sum(void); //prototype created
int main()
{
    sum();
return 0;
}
void sum()
{
    int a,b,sum=0;
    printf("Enter the first number:");
    scanf("%d",&a);
    printf("Enter the second number:");
    scanf("%d",&b);
    sum=a+b;
    printf("The sum is: %d",sum);
}
