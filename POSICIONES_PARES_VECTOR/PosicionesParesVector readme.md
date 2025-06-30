// PosicionesParesVector.c
// Programa que muestra los números almacenados en posiciones pares de un vector

#include <stdio.h>

int main() {
    int numeros[20]; // Array (vector) de 20 posiciones
    int i;

    // Bucle para ingresar los 20 números
    for (i = 0; i < 20; i++) {
        printf("Ingrese el número en la posición %d: ", i);
        scanf("%d", &numeros[i]);
    }

    // Mostrar los valores en posiciones pares
    printf("\n📍 Números en posiciones pares:\n");
    for (i = 0; i < 20; i++) {
        if (i % 2 == 0) { // Si el índice es par
            printf("Posición %d: %d\n", i, numeros[i]);
        }
    }

    return 0;
}

Declara un vector de 20 enteros (numeros[20]).

Usa un bucle for para pedir al usuario que ingrese un número en cada posición del vector.

Luego, otro bucle recorre el vector y verifica si la posición (índice i) es par usando i % 2 == 0.

Si la posición es par, muestra el número almacenado allí.

Sirve para practicar el uso de vectores y cómo acceder a posiciones específicas.
