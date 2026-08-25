## De cuatro notas sacar promedio (Forma sencilla)
Definir nota, suma,  como real 
	Definir w como entero 
	suma = 0 
	para w = 1 hasta 4 con paso 1 
		escribir " Digite su nota " 
		leer nota 
		suma = suma + nota 
	FinPara
    promedio = suma / 4 
	escribir "la nota promedio del estudiante es: " promedio 

## Como saber si un numero es primo 
definir num , i , d como entero
	Escribir "Digite su numero"
	leer num
	i = 1 
	d = 0 
	mientras i <= num Hacer
		si (num mod i = 0) entonces
			d = d + 1
		FinSi
		i = i + 1 
	FinMientras
	si d <= 2 entonces 
		escribir "El numero es primo" 
	sino 
		escribir "Este numero no es primo"
	FinSi

## Con un numero entero crre un cuadrado con el numero de lados que tenga
definir num ,  i como entero
	escribir "Digite un numero" 
	leer num 
	para i = 1 hasta num con paso 1 hacer 
		para j = 1 hasta num con paso 1 hacer 
		escribir " *" sin saltar 
	FinPara
	escribir ""
	FinPara

## Cuantos digitos tiene el numero dado 
definir num como entero
	escribir "Escriba el numero"
	leer num 
	contador = 0 
	mientras num > 0 hacer
		num = trunc ( num /10) 
		contador = contador + 1 
	FinMientras
	escribir "el numero tiene ",  contador ,  " digitos"
	FinProceso

## Cuantos numeros primos hay del 1 al numero dado 
definir num, j, d  , i Como Entero
	Escribir " Digite un numero"
	leer num 
	para j = 2 hasta num Hacer
		i = 1 
		d = 0 
		mientras i <= j Hacer
			si (j mod i = 0 ) entonces
				d = d + 1 
			FinSi
			i = i + 1
		FinMientras
		si d <= 2 entonces 
			primo = primo + 1 
			escribir j 
		FinSi
	FinPara
	escribir "hay", primo , "primos "

