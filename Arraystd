#include <stdio.h>
#include <conio.h>  // Some compilers may not require this or may not have it. 
                    // If your compiler complains, remove <conio.h> and getch().

struct student {
    int roll;
    char name[50];
    int m1, m2, m3;
    int tot;
    float per;
};

int main() {
    int n, i;
    struct student s[50];

    printf("Enter the number of students: ");
    scanf("%d", &n);

    // Input details for each student
    for (i = 0; i < n; i++) {
        printf("\nEnter Name, Roll No, Mark1, Mark2, Mark3 for student %d:\n", i+1);
        // %s will read a single word for name; if you need full names with spaces, 
        // consider using %[^\n] or similar approach.
        scanf("%s %d %d %d %d", 
              s[i].name, 
              &s[i].roll, 
              &s[i].m1, 
              &s[i].m2, 
              &s[i].m3);

        s[i].tot = s[i].m1 + s[i].m2 + s[i].m3;
        s[i].per = (float)s[i].tot / 3.0f;
    }

    // Display each student's details
    for (i = 0; i < n; i++) {
        printf("\n--- Student %d details ---\n", i+1);
        printf("Name      : %s\n",  s[i].name);
        printf("Roll No   : %d\n",  s[i].roll);
        printf("Mark 1    : %d\n",  s[i].m1);
        printf("Mark 2    : %d\n",  s[i].m2);
        printf("Mark 3    : %d\n",  s[i].m3);
        printf("Total     : %d\n",  s[i].tot);
        printf("Percentage: %.2f\n", s[i].per);
    }

    getch(); // If your environment doesn't support this, you can remove it.
    return 0;
}
