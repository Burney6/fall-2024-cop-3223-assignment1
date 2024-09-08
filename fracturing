#include <stdio.h>
#include <math.h>

// Compute distance between two points
double compDistance() {
    double x1, y1, x2, y2;

    printf("Enter first point: ");
    scanf("%lf %lf", &x1, &y1);
    printf("Enter second point: ");
    scanf("%lf %lf", &x2, &y2);

    return sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));
}

// Calc and display distance
double calcDistance()
{
    double distance=compDistance();
    printf("Distance between points: %.2f\n\n", distance);
    return 1;
}

// Calc and display perimeter
double calcPerimeter() {
    double diameter = compDistance();
    double perimeter = M_PI * diameter;
    printf("Perimeter between points: %.2f\n\n", perimeter);
    return 2;
}

// Calc and display area
double calcArea()
{
    double rad = compDistance() / 2.0;
    double area = M_PI * pow(rad,2);
    printf("Area of circle created from the two endpoints is: %.2f\n\n", area);
    return 3;
}

// Calc and display width
double calcWidth()
{
    double x1, y1, x2, y2;

    printf("Enter the coordinates of the first point: ");
    scanf("%lf %lf", &x1, &y1);
    printf("Enter the coordinates of the second point: ");
    scanf("%lf %lf", &x2, &y2);

    double width = fabs(x2 - x1);
    printf("Width of two points: %.2f\n\n", width);
    return 1;
}

// Calc and display height
double calcHeight()
{
    double x1, y1, x2, y2;

    printf("Enter the coordinates of the first point: ");
    scanf("%lf %lf", &x1, &y1);
    printf("Enter the coordinates of the second point: ");
    scanf("%lf %lf", &x2, &y2);

    double height = fabs(y2 - y1);
    printf("Height of two points: %.2f\n", height);
    return 2;
}

// Main Function
int main()
{
    calcDistance();
    calcPerimeter();
    calcArea();
    calcWidth();
    calcHeight();

    return 0;
}
