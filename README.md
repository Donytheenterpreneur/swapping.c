\\swapping.c
\\simple code for the swapping of two inputs a and b
#include<stdio.h>
int main()
{
	int a,b,temp;
	printf("enter two numbers: ");
	scanf("%d %d",&a,&b);
	temp=a;
	a=b;
	b=temp;
	printf("after swapping: a = %d\n, b = %d\n"a,b);
	return 0;
}

