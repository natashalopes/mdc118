# Prática 2

1. Faça um programa em C que leia três números reais e imprima a média aritmética destes números.
#include <stdio.h>
#include <assert.h>

int media(int valor1, int valor2, int valor3) {
    return (valor1 + valor2 + valor3) / 3;
}

//
// Seu teste
//
int main (){

    assert(7 == media(6, 7, 8));

    return 0;
}

2. Faça um programa em C que leia dois números inteiros e imprima o quociente e o resto da divisão entre eles.

3. Faça um programa em C que leia uma temperatura em graus Celsius e calcule o valor correspondente em graus Fahrenheit (°F = 9/5°C + 32).
#include <stdio.h>

int main (){
	
	float celsius, fahr;
	int  c = 167;
	
	printf("Digite uma temperatura em %cC : ", c);
	
	scanf("%f", &celsius);
	
	fahr = celsius*(9.0/5.0)+32;
	
	printf("%3.f%cC e o mesmo que %3.f%cF", celsius, c, fahr,c );
}

4. Faça um programa em C que leia a largura e o comprimento de um terreno em metros e calcule a sua área em hectares (1 hectare = 10.000 m²).

5. Faça um programa em C que leia o peso e a altura de uma pessoa e calcule o índice de massa corporal (imc = peso / altura²).

6. Faça um programa em C que leia o valor de compra, o ano de fabricação e o ano de depreciação e calcule o valor depreciado de um veículo (depreciação = (ano de depreciação - ano de fabricação) x 0,01 x valor de compra).

7. Faça um programa em C que leia o valor da hora de trabalho e o total de horas trabalhadas no mês e calcule o salário bruto, o salário líquido, e os impostos descontados. Considere IR igual a 25% e INSS igual a 11%.

8. Faça um programa em C que leia as coordenadas de dois pontos (x1, y1) e (x2, y2) e calcule a distância entre eles (d = raiz_quadrada((x2-x1)² + (y2-y1)²)).

9. Faça um programa em C que leia um número inteiro e imprima o caractere correspondente na tabela ASCII.
#include <stdio.h>
int main()
{
    char ch;
    printf("\nDigite um caracter: ");
    scanf("%c",&ch);
    printf("\nCaracter digitado: %c, Codigo ASCII: %d", ch, ch);
    return 0;
}

10. Faça um programa em C que leia um número inteiro e imprima a tabuada de multiplicação.
#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>

int main()
{
    int tabuada = 0;
    printf("\n\n\t\t\t\n>>> ");
    scanf("%i", &tabuada);

    for(int x = 1; x<=10; ++x){
        //1 x 5 = 5
        printf("%ix%i = %i\n", x, tabuada, x * tabuada);
    }

    return 0;
}
