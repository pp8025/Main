#include <stdio.h>
#include <conio.h>

void swap(int *x, int *y);

void main() {
    clrscr();
    int a, b;
    printf("Enter value of a & b: ");
    scanf("%d %d", &a, &b);

    printf("In Before swap: a=%d, b=%d", a, b);

    swap(&a, &b);

    getch();
}

void swap(int *x, int *y) {
    int z;
    z = *x;
    *x = *y;
    *y = z;

    printf("\nAfter swap:\n");
    printf("a=%d\n", *x);
    printf("b=%d\n", *y);
}
