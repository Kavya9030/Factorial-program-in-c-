# Factorial-program-in-c-
The Factorial Program in C calculates the factorial of a given positive integer using a for loop. The factorial of a number n is the product of all positive integers from 1 to n.



CODE:-
#include <stdio.h>

int main() {
    int n, i;
    long long factorial = 1;

    printf("Enter a number: ");
    scanf("%d", &n);

    if (n < 0) {
        printf("Factorial is not defined for negative numbers.\n");
    } else {
        for (i = 1; i <= n; i++) {
            factorial *= i;
        }

        printf("Factorial of %d = %lld\n", n, factorial);
    }

    return 0;
}


SAMPLE INPUT:-
Enter a number: 5


SAMPLE OUTPUT:-
Factorial of 5 = 120


FEATURES :-
*Calculates the factorial of a number.
*Uses a simple for loop.
*Easy and beginner-friendly.
*Uses basic arithmetic operations.
*Displays the calculated factorial.
