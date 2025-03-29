#include <stdio.h>

int main() {
    float cantidad;
    int opcion;
    const float USD_TO_GTQ = 7.75;  // 1 USD = 7.75 GTQ
    const float EUR_TO_GTQ = 8.40;  // 1 EUR = 8.40 GTQ
    const float EUR_TO_USD = 1.08;  // 1 EUR = 1.08 USD

    printf("CONVERSOR DE MONEDAS\n");
    printf("1. Quetzales a Dolares\n");
    printf("2. Quetzales a Euros\n");
    printf("3. Dolares a Quetzales\n");
    printf("4. Dolares a Euros\n");
    printf("5. Euros a Quetzales\n");
    printf("6. Euros a Dolares\n");
    printf("Seleccione una opcion: ");
    scanf("%d", &opcion);

    printf("Ingrese la cantidad a convertir: ");
    scanf("%f", &cantidad);

    switch(opcion) {
        case 1:
            printf("%.2f GTQ = %.2f USD\n", cantidad, cantidad / USD_TO_GTQ);
            break;
        case 2:
            printf("%.2f GTQ = %.2f EUR\n", cantidad, cantidad / EUR_TO_GTQ);
            break;
        case 3:
            printf("%.2f USD = %.2f GTQ\n", cantidad, cantidad * USD_TO_GTQ);
            break;
        case 4:
            printf("%.2f USD = %.2f EUR\n", cantidad, cantidad / EUR_TO_USD);
            break;
        case 5:
            printf("%.2f EUR = %.2f GTQ\n", cantidad, cantidad * EUR_TO_GTQ);
            break;
        case 6:
            printf("%.2f EUR = %.2f USD\n", cantidad, cantidad * EUR_TO_USD);
            break;
        default:
            printf("Opcion no valida\n");
    }

    return 0;
}
