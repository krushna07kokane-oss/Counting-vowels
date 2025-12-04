# Counting-vowels
#include <stdio.h>

int main() {
    char name[100];
    int i, count = 0;

    printf("Enter a string: ");
    scanf(" %[^\n]", name);

    for(i = 0; name[i] != '\0'; i++) {
        if(name[i]=='a' || name[i]=='e' || name[i]=='i' || name[i]=='o' || name[i]=='u' ||
           name[i]=='A' || name[i]=='E' || name[i]=='I' || name[i]=='O' || name[i]=='U') {
            count++;
        }
    }

    printf("Number of vowels in string = %d\n", count);

    return 0;
}
