// Programa que suma 20 números ingresados por el usuario

#include <stdio.h>

int main() {
    int i, numero, suma = 0; // Variables para el índice, el número y la suma total

    // Bucle para pedir 20 números
    for (i = 0; i < 20; i++) {
        printf("Ingrese el número #%d: ", i + 1);
        scanf("%d", &numero);
        suma += numero; // Acumular la suma
    }

    // Mostrar el resultado final
    printf("🔢 La suma total de los 20 números es: %d\n", suma);

    return 0;
}

Declara variables para contar (i), guardar el número ingresado (numero) y acumular la suma (suma).

Usa un bucle for que se repite 20 veces.

En cada vuelta del bucle:

Pide al usuario un número.

Lo lee con scanf.

Lo suma a la variable suma.

Después del bucle, muestra la suma total de los 20 números.

Es un programa básico para practicar entrada de datos y uso de bucles.







