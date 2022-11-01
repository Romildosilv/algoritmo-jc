# algoritmo-jc
Porcentagem 
//

#include <stdio.h>
#include <math.h>
double preco,total,desc;
int qtd;
 
int main(){
	
printf ("digite a quantida:");
scanf ("%d",&qtd);
printf ("\ndigite o preço:");
scanf ("%lf",&preco);
total=qtd*preco;
if (qtd<=5) {
	desc=preco*0.02;
	}
	else if (qtd>=6 && qtd<=10){
		desc=preco*0.03;
	 }
 else if (qtd>=10){
 	desc=preco*0.05;
 }
 
		printf ("\no total e R$%.2lf\n",total-desc);
	return 0;
}
