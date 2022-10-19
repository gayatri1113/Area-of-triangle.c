//# Area-of-triangle.c//
#include<stdio.h>
int main()
{
    float h,b,area;
    printf("enter height");
    scanf("%f",&h);
    printf("enter base");
    scanf("%f",&b);
    area=(h*b)/2;
    printf("Area of triangle=%f",area);
    return 0;
}
