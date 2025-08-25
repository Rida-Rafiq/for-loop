# for-loop
A simple C program that prints the multiplication table for a number entered by the user. Demonstrates the use of for loops and basic input/output in C.
# Multiplication Table in C

This C program generates the multiplication table for a number provided by the user. It demonstrates the use of loops and basic input/output operations in C.

## Features

- Prints the multiplication table from 1 to 10
- Takes user input for the desired number
- Simple and easy-to-understand code for beginners

## Code Example

```c
#include <stdio.h>

int main() {
    int num;
    printf("Enter table number: ");
    scanf("%d", &num);

    for(int i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num * i);
    }

    return 0;
}
