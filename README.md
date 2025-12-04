# string-operations
#include <stdio.h>


int stringLength(char str[]) {
    int i = 0;
    while (str[i] != '\0') {
        i++;
    }
    return i;
}

int main() {
    char number[50];

    printf("Enter a number: ");
    scanf("%s", number);  

    int digitCount = stringLength(number);

    printf("Number of digits = %d\n", digitCount);

    return 0;
}



