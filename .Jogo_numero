#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
#include <windows.h>

int main()
{
   setlocale(LC_ALL, "Portuguese");
   system("color 2f");
   printf("\n\n");
   printf("\t\n ----------JOGO O NÚMERO SECRETO--------\n\n");
   printf("\n\tANTES DE INICIARMOS EU PRECISO SABER? \n\n");
   char nome[80];
   int idade,  chute=0, acertou,contador, tentativa = 5,maior, numero_secreto=0;
   
   printf("\t\nQUAL É O SEU NOME: ");
   scanf("%[^\n]",nome);
   
   
   
   printf("\t\nINFORME A SUA IDADE: ");
   scanf("%i", &idade);
   
   if(idade <=11){
	   printf("\tQUE PENA! SO PODE JOGAR COM A IDADE ACIMA DE 11 ANOS!\n");
	   
	   exit(0);
   }
   setlocale(LC_ALL, "Portuguese");
   
   	printf("\n\tBEM-VINDO AO JOGO DE ADIVUNHAÇÃO!\n\n");
   printf("\n\n");
   printf("\n\tVAMOS INICIAR O JOGO PARA VOCÊ: %s.",nome);
   printf("\n\n\n");
   
   numero_secreto=147;
   
   	
   	for(contador = 0; contador < tentativa; contador++){
		   
		   printf("\t\nQUAL É O NÚMERO SECRETO ENTRE 1 À 220 -  %dª TENTATIVA DE %d...: ",contador+1,tentativa );
        scanf("%d",&chute);
        printf("\n");
	  
	    acertou= (numero_secreto == chute);
	    
	    if (acertou){
	    	
		printf("PARABÉNS!%s VOCÊ ACERTOU!", nome);
		printf("\n");
		
		break;	
		}
	    	
	    	    
	    maior= (numero_secreto > chute);
	    
	    if (maior){
		printf("O NUMERO SECRETO É MAIOR");	
		printf("\n");
		}
	    	
	    else{
			printf("NUMERO SECRETO É MENOR");
			printf("\n");
		}
	    
   
   
	   }
	   
	   return 0;
}
