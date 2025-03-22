#include <stdio.h>
#include <conio.h>

void upper(char str[10]);

void main() {
    char s[10];
    clrscr();
    printf("Enter string: ");
    fflushall();
    gets(s);      // Note: gets() is unsafe; consider using fgets() instead
    upper(s);
    getch();
}

void upper(char str[10]) {
    int i;
    for (i = 0; str[i] != '\0'; i++) {
        if (str[i] >= 'a' && str[i] <= 'z') {
            str[i] = str[i] - 32;
        }
    }
    printf("Converted string: ");
    puts(str);
}
