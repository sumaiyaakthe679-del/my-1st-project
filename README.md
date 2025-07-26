# my-st-projectm

#include <stdio.h>

int main() {
    int a, b;

    // Input from user
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    // Swapping without third variable
    a = a + b;
    b = a - b;
    a = a - b;

    // Output after swapping
    printf("After swapping: a = %d, b = %d\n", a, b);

    return 0;
}
