#include <stdio.h>
#include <conio.h>

void main() {
    int a[10], i, j, n, temp;
    clrscr();

    printf("Enter the limit: ");
    scanf("%d", &n);

    printf("Enter the elements: ");
    for (i = 0; i < n; i++) {
        scanf("%d", &a[i]);
    }

    printf("Entered elements: ");
    for (i = 0; i < n; i++) {
        printf("%d ", a[i]);
    }

    // Sorting in descending order
    for (i = 0; i < n - 1; i++) {
        for (j = i + 1; j < n; j++) {
            if (a[i] < a[j]) {
                temp = a[i];
                a[i] = a[j];
                a[j] = temp;
            }
        }
    }

    printf("\nArray sorted in descending order: ");
    for (i = 0; i < n; i++) {
        printf("%d ", a[i]);
    }

    getch();
}
