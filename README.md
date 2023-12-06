#include <stdio.h>
#include <math.h>

int main()
{
  int t=25;
  int h=65;
  int w=20;
  double k=0;
  k=0.5*pow(t,2)-0.2*h+0.1*w-15;
  if(k>300)
  printf("sunny");
  else if (200<k && k<=300)
  printf("cloudy");
  else if (100<k && k<=200)
  printf("rainy");
  else if(k<=100)
  printf("stormy");

  return 0;
}
