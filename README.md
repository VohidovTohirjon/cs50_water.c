/*cs50_water.c
CS50 course first question without using cs50.h*/
#include <stdio.h>
int main(void)
{
    int i;
    printf("How many minutes did you have a shower (Write positive integer): ");
    scanf("%d", &i);
    if (i > 0)
        printf("You spent %d litres of water, bro just make shower with fewer water, please think about other regions!", i * 12);
        else
        printf("You wrote a non-positive integer, run it again and write positive number, dude");
}
