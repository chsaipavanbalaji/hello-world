
//Write a program to display prime numbers between 1 to 100
#include<stdio.h>
void main()
{
	int num,dcount,i;
	for(num=1;num<=100;num++)
	{
		dcount=0;
		for(i=1;i<=num;i++)
		{
			if(num%i==0)
			{
				dcount=dcount+1;
			}
		}
		if(dcount==2)
		{
			printf("%d\n",num);
		}
	}
}
