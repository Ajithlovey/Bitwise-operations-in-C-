# Bitwise-operations-in-C-
#include <stdio.h>

int main() {
    int a = 5, b = 9; // In binary: a = 0101, b = 1001
    int result;

    result = a & b;   // AND
    printf("a & b = %d\n", result);  // Output: 1 (0001)

    result = a | b;   // OR
    printf("a | b = %d\n", result);  // Output: 13 (1101)

    result = a ^ b;   // XOR
    printf("a ^ b = %d\n", result);  // Output: 12 (1100)

    result = ~a;      // NOT
    printf("~a = %d\n", result);     // Output: -6 (in two's complement: ~0101 = 1010)

    result = a << 1;  // Left shift by 1 (multiply by 2)
    printf("a << 1 = %d\n", result); // Output: 10 (1010)

    result = b >> 1;  // Right shift by 1 (divide by 2)
    printf("b >> 1 = %d\n", result); // Output: 4 (0100)

    return 0;
}

Output
a & b = 1
a | b = 13
a ^ b = 12
~a = -6
a << 1 = 10
b >> 1 = 4
