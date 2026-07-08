//sum kora

#include <stdio.h>

int addNumbers(int a, int b)
{
    return a + b;
}

int main()
{
    int a, b, sum;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    sum = addNumbers(a, b);

    printf("Sum = %d\n", sum);

    return 0;
}
