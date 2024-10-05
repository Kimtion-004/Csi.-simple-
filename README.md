# Csi.-simple-#include<stdio.h>

int main() 
{
float p, r, A, n, t, ci ;
printf("Enter the principle amount, \n") ;
scanf("%f", & p) ;
printf("Enter the rate") ;
scanf("%f", & r) ;
printf("Enter the time in years") ;
scanf("%f", &t);
printf("Enter the number of years");
scanf("%f", &n);


ci=p*pow((1 + r/n), (n*t)) ;

printf("ci=%f", & ci) ;
 
 return 0;
     }
