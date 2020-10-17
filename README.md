Algoritmo numeros_xd
	Definir n,i,num Como Entero;
	Definir grupo1,grupo2 Como Caracter;
	grupo1<-""; grupo2<-"";
	n<-1; i<-1;
	Repetir
		Escribir 'Ingrese el valor de N: ';
		Leer n;
	Mientras Que n<0
	Para i<- 1 Hasta n Hacer
		num <- azar(100);
		Escribir num;
		Si num % 2 = 0 Entonces
			grupo1<-grupo1 + " " + CONVERTIRATEXTO(num);
		SiNo
			grupo2<-grupo2 + " " + CONVERTIRATEXTO(num);
		Fin Si
	Fin Para
	Escribir " Numero compuesto: ", grupo1;
	Escribir " Numero primo: ", grupo2;
FinAlgoritmo
