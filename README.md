# Repositorio
lineas de codigo del primer integrante
Algoritmo seriefibonacci
	definir serie0, serie1,serie3, ningresado como real;
	serie0 <-0
	serie1 <-1
	Escribir "Este programa fue diseñado para calcular la serie de fibonacci de cualquier numero entero...";
	escribir"Favor de ingresar el numero a calcular..";
	leer ningresado;
	si ningresado<0 Entonces
		Escribir "El numero ingresado debe ser positivo."
	sino 
		para serie3<-1 hasta ningresado Hacer
			Escribir ,serie0
			serie3<-serie0 + serie1
			serie0<-serie1
			serie1<-serie3
			serie3<-serie0 + serie
		FinPara
	FinSi
	
FinAlgoritmo

Lineas de codigo del segundo integrante
Algoritmo Piramide  
	Definir alt,b,c,numniveles Como Entero
	Definir lenum Como Caracter 
	Escribir " Introduce el numero de niveles que deseas bro: "; 
	Leer numniveles
	Escribir " Ingresa tu caracter papito: ";
	Leer lenum
	si  (numniveles<0)Entonces
		Escribir "Solo numeros positivos rey"
	FinSi
	Para alt = numniveles Hasta 1 Con Paso -1 hacer
		para b=1 Hasta alt con paso 1 Hacer
			Escribir " " Sin Saltar
		FinPara
		
		para c = alt hasta numniveles con paso 1 hacer
			Escribir " ", lenum;  Sin Saltar
		FinPara
		Escribir " "
	FinPara
	
FinAlgoritmo

lienas de codigo del tercer integrante
Algoritmo aram
Definir operacion Como Entero
Escribir "aqui se encuentra el codigo del  integrante 3";
Escribir "selecciona una operacion";
Escribir "1.- suma";
Escribir "2.- resta";
Escribir "3.- multiplicacion";
Escribir "4.- div";
Escribir "5.- potencia";
Escribir "6.- factorial";
Leer operacion;
segun operacion Hacer
1:
Definir n1, n2, n3, n4, n5, n6, n7, n8, n9, n10, r Como Real;
Definir digitos Como Real
Escribir "¿Cuantos digitos desea sumar?"
leer digitos;
Segun digitos hacer
2:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2;
r=  n1 + n2;
Escribir "El resultado de la suma es: ", r;
3:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3;
r=  n1 + n2 + n3;
Escribir "El resultado de la suma es: ", r;
4:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4;
r=  n1 + n2 + n3 + n4;
Escribir "El resultado de la suma es: ", r;
5:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4, n5;
r=  n1 + n2 + n3 + n4 + n5;
Escribir "El resultado de la suma es: ", r;
6:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4, n5, n6;
r=  n1 + n2 + n3 + n4 + n5 + n6;
Escribir "El resultado de la suma es: ", r;
7:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4, n5, n6, n7;
r=  n1 + n2 + n3 + n4 + n5 + n6 + n7;
Escribir "El resultado de la suma es: ", r;
8:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4, n5, n6, n7, n8;
r=  n1 + n2 + n3 + n4 + n5 + n6 + n7 + n8;
Escribir "El resultado de la suma es: ", r;
9:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9;
r=  n1 + n2 + n3 + n4 + n5 + n6 + n7 + n8 + n9;
Escribir "El resultado de la suma es: ", r;
10:Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9, n10;
r=  n1 + n2 + n3 + n4 + n5 + n6 + n7 + n8 + n9 + n10;
Escribir "El resultado de la suma es: ", r;
Escribir "Ingresa los valores la tu suma";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9, n10;
r=  n1 + n2 + n3 + n4 + n5 + n6 + n7 + n8 + n9 + n10;
Escribir "El resultado de la suma es: ", r;
FinSegun
2:
Escribir "Ingresa los valores de la resta";
Escribir "¿Cuantos digitos desea restar?"
leer digitos;
Segun digitos hacer
2:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2;
r=  n1 - n2;
Escribir "El resultado de la resta es: ", r;
3:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3;
r=  n1 -  n2 - n3;
Escribir "El resultado de la resta es: ", r;
4:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3, n4;
r=  n1 - n2 - n3 - n4;
Escribir "El resultado de la resta es: ", r;
5:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3, n4, n5;
r=  n1 - n2 - n3 - n4 - n5;
Escribir "El resultado de la resta es: ", r;
6:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3, n4, n5, n6;
rr=  n1 - n2 - n3 - n4 - n5 - n6;
Escribir "El resultado de la resta es: ", r;
7:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3, n4, n5, n6, n7;
r=  n1 - n2 - n3 - n4 - n5 - n6 - n7;
Escribir "El resultado de la resta es: ", r;
8:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3, n4, n5, n6, n7, n8;
r=  n1 - n2 - n3 - n4 - n5 - n6 - n7 - n8;
Escribir "El resultado de la resta es: ", r;
9:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9;
r=  n1 - n2 - n3 - n4 - n5 - n6 - n7 - n8 - n9;
Escribir "El resultado de la resta es: ", r;
10:Escribir "Ingresa los valores la tu resta";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9, n10;
r=  n1 - n2 - n3 - n4 - n5 - n6 - n7 - n8 - n9 - n10;
Escribir "El resultado de la resta es: ", r;
FinSegun
3:
Escribir "Ingresa los valores de la multiplicacion";
Escribir "¿Cuantos digitos desea multiplicacion?"
leer digitos;
Segun digitos hacer
2:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2;
r=  n1 * n2;
Escribir "El resultado de la multiplicacion es: ", r;
3:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3;
r=  n1 *  n2 * n3;
Escribir "El resultado de la multiplicacion es: ", r;
4:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3, n4;
r=  n1 * n2 *n3 * n4;
Escribir "El resultado de la multiplicacion es: ", r;
5:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3, n4, n5;
r=  n1 * n2 * n3 * n4 * n5;
Escribir "El resultado de la multiplicacion es: ", r;
6:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3, n4, n5, n6;
r=  n1 * n2 * n3 * n4 * n5 * n6;
Escribir "El resultado de la multiplicacion es: ", r;
7:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3, n4, n5, n6, n7;
r=  n1 * n2 * n3 * n4 * n5 * n6 * n7:
Escribir "El resultado de la multiplicacion es: ", r;
8:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3, n4, n5, n6, n7, n8;
r=  n1 * n2 * n3 * n4 * n5 *n6 * n7 * n8;
Escribir "El resultado de la multiplicacion es: ", r;
9:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9;
r=  n1 * n2 * n3 * n4 * n5 * n6 * n7 * n8 * n9;
Escribir "El resultado de la multiplicacion es: ", r;
10:Escribir "Ingresa los valores la tu multiplicacion";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9, n10;
r=  n1 * n2 * n3 * n4 * n5 * n6 * n7 * n8 * n9 * n10;
Escribir "El resultado de la multiplicacion es: ", r;
FinSegun
4:
Escribir "Ingresa los valores de la div";
Escribir "¿Cuantos digitos desea div?"
leer digitos;
Segun digitos hacer
2:Escribir "Ingresa los valores la  div";
Leer  n1, n2;
r=  n1 / n2;
Escribir "El resultado de la div es: ", r;
3:Escribir "Ingresa los valores la  div";
Leer  n1, n2, n3;
r=  n1 /  n2 / n3;
Escribir "El resultado de la div es: ", r;
4:Escribir "Ingresa los valores la  div";
Leer  n1, n2, n3, n4;
r=  n1 / n2 / n3 / n4;
Escribir "El resultado de la div es: ", r;
5:Escribir "Ingresa los valores la  div";
Leer  n1, n2, n3, n4, n5;
r=  n1 / n2 / n3 / n4 / n5;
Escribir "El resultado de la div es: ", r;
6:Escribir "Ingresa los valores la  div";
Leer  n1, n2, n3, n4, n5, n6;
r=  n1 / n2 / n3 / n4 / n5 / n6;
Escribir "El resultado de la div es: ", r;
7:Escribir "Ingresa los valores la  div";
Leer  n1, n2, n3, n4, n5, n6, n7;
r=  n1 / n2 / n3 / n4 / n5 / n6 / n7;
Escribir "El resultado de la div es: ", r;
8:Escribir "Ingresa los valores la  div";
Leer  n1, n2, n3, n4, n5, n6, n7, n8;
r=  n1 / n2 / n3 / n4 / n5 / n6 / n7 / n8;
Escribir "El resultado de la div es: ", r;
9:Escribir "Ingresa los valores la  div";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9;
r=  n1 / n2 / n3 / n4 / n5 / n6 / n7 / n8 / n9;
Escribir "El resultado de la div es: ", r;
10:Escribir "Ingresa los valores la div";
Leer  n1, n2, n3, n4, n5, n6, n7, n8, n9, n10;
r=  n1 / n2 / n3 / n4 / n5 / n6 / n7 / n8 / n9 / n10;
Escribir "El resultado de la div es: ", r;
FinSegun
5:
Definir cuad como entero
Escribir "Ingresa los valores de la potencia";

Leer  n1;
cuad=  n1 ^3;
Escribir "El resultado de la potencia es: ", cuad;
6:

Escribir "Ingresa los valores la  factorial";
Leer n1;
cont<-0
fact<-1
repetir
fact<-fact*n1
cont<-cont+1
hasta que (cont<=n1)
Escribir "El resultado de la factorial es: ", r;

FinSegun
FinAlgoritmo