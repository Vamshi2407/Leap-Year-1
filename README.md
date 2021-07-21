# Leap-Year-1
Enter the Year and It will show whether it's a Leap Year or not



#include <stdio.h>
int main()
{ 
int year;
printf("Enter a year: ");
scanf("%d",&year);
if(year%4 == 0)
 {
if( year%100 == 0)
 { // year is divisible by 400, hence the year is a leap year
  if ( year%400 == 0) 
  printf("%d is a leap year.", year); 
  else 
  printf("%d is not a leap year.", year);
   }
    else
     printf("%d is a leap year.", year );
 }
      else printf("%d is not a leap year.",year);
      return 0;
}
