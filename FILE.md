Write the C code to find the radius of a circle?

#include <stdio.h>

int main() {
    float r,Pi=3.14;
    printf("Enter radius value");//Get user input to the radius of the circle
    scanf("%f",&r);
    
    printf("Area of the circle:%f",Pi*r*r);//Give the area of the cicle
    
    return 0;
}
