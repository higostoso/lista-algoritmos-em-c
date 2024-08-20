# lista-algoritmos-em-c
1- Hello, Word!
#include <stdio.h> 
int main(){
	printf("hello, Word!\n");
}
2- soma de dois numeros
#include <stdio.h>

int main (){
	int num1;
	int num2;
	int soma;
	
	printf("digite um numero:");
	scanf("%d", &num1);
	printf("digite outro numero:");
	scanf("%d", &num2);
	
	soma = num1 + num2;
    printf("A soma de %d e %d é %d\n", num1, num2, soma);
	
	
	return 0;
	
}
3- impar ou par
#include <stdio.h>

int main (){
	int numero;
	int par, impar;
	
	printf("digite um numero:");
	scanf("%d", &numero);
	
	  if (numero % 2 == 0) {
        printf("O número %d é par.\n", numero);
    } else {
        printf("O número %d é ímpar.\n", numero);
    }


}
4- Maior de Dois Números
#include <stdio.h>

int main (){
	int numero1;
	int numero2;
	
	printf("digite um numero:");
	scanf("%d", &numero1);
	printf("digite outro numero:");
	scanf("%d", &numero2);
	
	  if (numero1 > numero2) {
        printf("O número %d e maior\n", numero1);
    } else {
        printf("O número %d é maior\n", numero2);
    }


}
5- cacular a media

#include <stdio.h>

int main() {
    int num1, num2, num3;
    float media;


    printf("Digite o primeiro número: ");
    scanf("%d", &num1);
    
    printf("Digite o segundo número: ");
    scanf("%d", &num2);

    printf("Digite o terceiro número: ");
    scanf("%d", &num3);

    media = (num1 + num2 + num3) / 3.0;
    
    printf("A média aritmética dos números %d, %d e %d é %.2f\n", num1, num2, num3, media);

    return 0;
}
6- Cálculo da Área de um Círculo

