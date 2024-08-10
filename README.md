#include <stdio.h>

int main() {
    int opcion;

    // Solicitar al usuario que ingrese una opción
    printf("Ingrese 1 para 'i like pizza' o 2 para 'i like burgers': ");
    scanf("%d", &opcion);

    // Evaluar la opción ingresada
    if (opcion == 1) {
        printf("i like pizza\n");
    } else if (opcion == 2) {
        printf("i like burgers\n");
    } else {
        printf("Opción no válida\n");
    }

    return 0;
}
