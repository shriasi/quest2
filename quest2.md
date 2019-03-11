# quest2
find leap year
//this program is to print leap year or not
#include<stdio.h>
int main(void)//main begins
{
    int year;
//input
    printf("Enter a year:");
    scanf("%d",&year);
    
//conditions
    if(year/400 == 0)
    printf("This is a leap year\n");
    else
        printf("This is not a leap year");

return 0;
}//end main
