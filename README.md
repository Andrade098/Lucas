# Lista 2 (exercicio 1)
#include <stdio.h>
#include <stdlib.h>
#include <locale.h>

int main() {
	
	int num;
	
	printf("Digite algum dos numeros a seguir (11,19,21,27,31,32,61 ou 71): ");
	scanf ("%d", &num);
	switch (num)
	{
		case 61:
			printf("\n\nO id dessa cidade e Brasilia.\n");
		break;
		case 71:
			printf("\n\nO id dessa cidade e Salvador.\n");
		break;
		case 11:
			printf("\n\nO id dessa cidade e Sao Paulo.\n");
		break;
		case 21:
			printf("\n\nO id dessa cidade e Rio de Janeiro.\n");
		break;
		case 32:
			printf("\n\nO id dessa cidade e Juiz de Fora.\n");
		break;
		case 19:
			printf("\n\nO id dessa cidade e Campinas.\n");
		break;
		case 27:
			printf("\n\nO id dessa cidade e Vitoria.\n");
		break;
		case 31:
			printf("\n\nO id dessa cidade e Belo Horizonte.\n");
		break;
		default:
			printf("\n\nO id que voce digitou eh invalido. \n");
	}
return(0);		
}
