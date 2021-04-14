# Prática 1

1. Faça um programa em C que calcule a média final a partir da fórmula (0,4 x A1) + (0,6 x A2). Considere A1 e A2 números reais entre 0 a 10.
#include<stdio.h>
#incluide<stlib.h>
int main(void)
{
  float  A1, A2, media;
  
  printf(0,4 x A1);
  scanf("%f",&0,4 x A1);
  
  printf(0,6 x A2);
  scanf("%f",%0,6 x A2);
  
  media = ((0,4 x A1) + (0,6 x A2)) / 2;
  
  printf(" media = %.2f\n",media);
  
2. Faça um programa em C que calcule a área de um triângulo (a = base x altura / 2). Considere base e altura números inteiros maior que 0.
#include <cstdlib>
#include <iostream>
 
int main()
 
{
int b=0,h=0;
float area=0;
 
printf(“Digite o valor da base: “);
scanf(“%i”,&b);
printf(“\nDigite o valor da altura: “);
scanf(“%i”,&h);
 
area=(b*h)/2;
 
printf(“\n\nO valor da area do triangulo é igual a: %f\n\n”,area);
 

3. Faça um programa em C que calcule o perímetro de uma pizza (P = 2 x PI x r). Considere o raio um número inteiro e a constante PI igual a 3,1416.
#include <cstdlib>
#include <iostream>
 
int main()
 
{
float P, r; 
constante PI = 3,1416;
 
printf(“ valor do p: “);
scanf(“%i”,&p);
printf(“ valor do r: “);
scanf(“%i”,&r);
 
P = 2 x PI x r);
 
printf(“\n\nO valor do perimetro igual a: %f2xPIxr”);
 

4. Faça um programa que C que calcule os impostos incluídos no preço de um produto (preço final = (1 + ICMS + COFINS + PIS/PASEP) x preço inicial). Considere ICMS igual a 17%, COFINS igual a 7,6% e PIS/PASEP igual a 1,65%.

5. Faça um programa em C que converta um valor qualquer em Gigabytes para um valor em bytes (1GB = 1024³Bytes).

6. Faça um programa em C que calcule as raízes de uma equação do 2° grau através da fórmula de Bhaskara (-b +/- raiz_quadrada(b² - 4ac)/2a).

7. Faça um programa em C que calcule a altura alcançada por um avião após ter percorrido uma certa distância (seno(ângulo) = altura/distância). Considere o ângulo de inclinação do avião menor ou igual a 45°.

8. Faça um programa em C que converta um tempo expresso em segundos para um valor em horas, minutos e segundos (ex.: 1000 segundos corresponde a 0 horas 16 minutos e 40 segundos).
#include <stdio.h>
#include <stdlib.h>

int main() {
    int segundos, h, m, s, resto;

    printf("Digite uma quantidade de segundos: ");
    scanf("%d", &segundos);
    
    h = segundos / 3600;
    resto = segundos % 3600;
    m = resto / 60;
    s = resto % 60;
    printf("%d:%d:%d\n", h, m, s);

    return 0;
}
9. Faça um programa em C que converta uma idade expressa em anos, meses e dias para um valor em dias. Considere um ano com 365 dias e um mês com 30 dias.
#include <stdio.h>

int main () {

   

   int idade, idadeEmDias;  // iniciando as variáveis

   

   printf("Digite sua idade em dias: ");  // mostra o valor na tela

   scanf("%d", &idadeEmDias);  // captura o valor digitado pelo usuário

   

   idade = idadeEmDias / 365;  // converte a idade em dias para idade em anos

   

   printf("Até agora você viveu %d anos, %d meses e %d dias.",  

   idade, idade * 12, idade * 365);  // mostra o resultado final

   

   return 0;  // encerra o programa com o código 0 (Success)

   

}  
10. Faça um programa em C que calcule a decomposição de um número inteiro qualquer em unidade, dezena, centena e milhar (ex.: 5637 é decomposto em 7 unidades, 3 dezenas, 6 centenas e 5 milhares).
