#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>
#include <time.h>
bool ePar(int x){
 bool retorno = false;
 if(x % 2 == 0)
 retorno = true;
 else
 retorno = false;
 return retorno;
}
void parImpar()
{
    int maoComputador = 0;
 int maoJogador = 0;
 int jogadorEscolheParOuImpar = 0;
 bool par = true;
 srand(time(0));
 maoComputador = rand() % 10;
 //printf("%d, Computador: \n",maoComputador);
 printf("\t\t\tEVEN OR ODD GAME");
 printf("\n\nEnter a number between 0-9: ");
 scanf("%d",&maoJogador);
 printf("\nThe computer has already chosen the number!");
 printf("\nCHOOSE BETWEEN:\n\t[1]-->EVEN NUMBER\n\t[2]-->ODD NUMBER\n");
 scanf("%d", &jogadorEscolheParOuImpar);
 if(jogadorEscolheParOuImpar == 1){
 par = true;
 }
 else{
 par = false;
 }
 printf("\n\nCOMPUTER HAND %d, YOUR HAND %d, TOTAL= %d ", maoComputador,maoJogador,
maoComputador+maoJogador);
 if((ePar(maoComputador+maoJogador) && par) || (!ePar(maoComputador+maoJogador) && !
par)){
 printf("\nYOU'RE A WINNER!!");
 }
 else{
 printf("YOU'RE A LOSER!\a\a\a");
 }
 return 0;
}
int main()
{

 int i =0;
 while(i!=2)
 {
    system("cls");
    i=0;
    parImpar();
    printf("\n-------->DO YOU WANNA PLAY AGAIN?\n\t\t\t[ANY NUMBER]->YES\n\t\t\t[2]->NO");
    scanf("%d",&i);


 }
 printf("THE GAME IS OVER, TOTALLY LEAVE YOU :(");

}
