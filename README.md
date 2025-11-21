# Pr-ctica-7-
Estructura de selección 
#include <stdio.h>

int main()
{
    int a, b;

    printf("Dame un número: ");
    scanf("%d", &a);

    printf("Dame otro número: ");
    scanf("%d", &b);

    if (a > b)
    {
        printf("\ta (%d) es mayor que b (%d).\n", a, b);
    }
    else if (b > a)
    {
        printf("\tb (%d) es mayor que a (%d).\n", b, a);
    }
    else
    {
        printf("\ta (%d) y b (%d) son iguales.\n", a, b);
    }

    printf("\tEl programa sigue su flujo.\n");

    return 0;
}
