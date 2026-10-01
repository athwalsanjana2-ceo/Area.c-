/* WAP to calculate Area of Rectangle */
#include <stdio.h>
#include <conio.h>
void main()
{
    float l, b, area;
    clrscr();
    printf("\nEnter the length = \n");
    scanf("%f", &l);
    printf("\nEnter the breadth = \n");
    scanf("%f", &b);
    area = l * b;
    printf("\nArea of Rectangle is = %f", area);
    getch();
}
