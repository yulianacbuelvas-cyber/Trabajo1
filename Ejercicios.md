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

