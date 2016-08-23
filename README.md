#include<stdio.h>
#include<stdlib.h>

int main()
{
  
  printf("Welcome to GitHub");
  int x, y, z;
  printf("Enter two nos:");
  scanf("%d %d ",&x, &y);
  z=sum(x,y);
  printf("sum is =%d",&z);
  return 0;
}

int sum(int a, int b)
{
	int a, b, c;
	c=a+b;
	return c;
}
