                                                                    Multiplo de 3

// MultiploDeTres.c
// Programa que verifica si un número es múltiplo de 3

#include <stdio.h>

int main() {
    int numero; // Variable para guardar el número ingresado

    // Pedimos al usuario que ingrese un número
    printf("Ingrese un número: ");
    scanf("%d", &numero);

    // Verificamos si el número es múltiplo de 3
    if (numero % 3 == 0) {
        printf("✅ El número %d es múltiplo de 3\n", numero);
    } else {
        printf("❌ El número %d NO es múltiplo de 3\n", numero);
    }

    return 0;
}


Este programa lo que hace es pedirle al usuario que ingrese un numero y lo q va a hacer el programa es calcular si el numero  ingresado es multiplo de 3 y sino lo es le pide al usuario que ingrese otro numero.