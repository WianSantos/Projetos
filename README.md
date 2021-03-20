#include <stdio.h>
#define clearScreen() printf("\033[H\033[J")
int main (void){

  char nome [30] = " ";
  char ano [30] = " "; 


clearScreen();

  printf("Defina o nome do aluno: ");
  scanf("%s", nome);

  printf("Defina o ano de nascimento: ");
  scanf("%s", ano);

printf ("O nome do aluno é %s e o ano do nascimento dele foi em %s\n", nome, ano);
return 0;
}
