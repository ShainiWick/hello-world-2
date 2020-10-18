Write C code to add two numbers?

#include <stdio.h>
int main()
{
  int x, y, z;

  printf("Enter two numbers to add\n");
  scanf("%d%d", &x, &y);//take user inputs

  z = x + y;

  printf("Sum of the numbers = %d\n", z);//print the sum

  return 0;
}
