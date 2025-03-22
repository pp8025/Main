#include <stdio.h>
#include <conio.h>
#include <string.h>

void main() {
    char str[20], rev[20];
    int i, j, len;
    clrscr();

    printf("Enter string: ");
    gets(str);  // Note: gets() is unsafe; consider using fgets() instead

    len = strlen(str);

    // Reverse the string
    for (i = len - 1, j = 0; i >= 0; i--, j++) {
        rev[j] = str[i];
    }
    rev[j] = '\0';

    // Check if original string and reversed string are the same
    if (strcmp(str, rev) == 0) {
        printf("Entered string is a Palindrome");
    } else {
        printf("Not Palindrome");
    }

    getch();
}
