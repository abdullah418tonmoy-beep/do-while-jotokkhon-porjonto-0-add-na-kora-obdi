
#include<stdio.h>
int main()
{
    int i,s=0;

    do
    {
        printf("enter a number :");
        scanf("%d",&i);
         s=s+i;
    }
   while(i!=0); // মানে আমি যতক্ষন না ০ ইন্টার দিব তত গুলা জগ করবে এইখানে
printf("sum= %d",s);

    return 0;
}
