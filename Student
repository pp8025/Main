#include <stdio.h>
#include <conio.h>  // If your compiler doesn't support conio.h, remove it and getch()

struct student {
    int roll;
    char name[20];  // Increased size to safely store longer names
    float marks;
};

int main() {
    struct student s;

    // If you're using an older Turbo C compiler, you can use clrscr() here
    // clrscr(); 

    printf("Enter Roll No: ");
    scanf("%d", &s.roll);

    // Flush any leftover input so the name input isn't skipped
    fflush(stdin);

    printf("Enter Name: ");
    gets(s.name);  // gets() is unsafe in production, but used in older C programs
                   // For safer code, use fgets(s.name, sizeof(s.name), stdin).

    printf("Enter Marks: ");
    scanf("%f", &s.marks);

    // Display the data
    printf("\n--- Student Details ---\n");
    printf("Name  : %s\n", s.name);
    printf("Roll  : %d\n", s.roll);
    printf("Marks : %.2f\n", s.marks);

    getch();  // Remove if unsupported
    return 0;
}
