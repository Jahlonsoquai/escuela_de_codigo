### Ejercicio Calificaciones.

Realizar programa que muestre, el numero de calificaciones mayores a 7 y menores a 7. Además que solo admita calificaciones entre 0 y 10, es decir no cal<0 ni cal>10.

1.- Inicio
2.- Calif<-0
3.- i<-0
4.- CalMay7<-0
5.- CalMen7<-0
6.- 
Mientras i<10 Hacer 
	i=i+1
	Mientras Calif<=10 y Calif>0	
	Escribir ("Ingresa la calificación ", i)
	Leer Calif
	FInMientras
Si Calif<7 Entonces
	CalMen7<-CalMen7+1
SiNo 	
CalMay7<-CalMay7+1
FinSi
FinMientras

7.- Escribir "El total de Calificación mayores a 7, son: ", CalMay7.

* En PSeInt.

Algoritmo Calificaciones
	
	Calif<-0
	i<-0
	CalMay7<-0
	CalMen7<-0
	
	Mientras i<10 Hacer
		i=i+1
		 
		Mientras Calif>10 o Calif<0 Hacer
				Escribir "Rango de calificación incorrecto Ingresa Calificación con valor de entre 0 a 10"
				Leer Calif
			Fin Mientras
		
		Escribir "Ingresa Calificación", i
		Leer Calif
		
		Si Calif<7 Entonces
			CalMen7<-CalMen7+1
			
		SiNo
			CalMay7<-CalMay7+1
			
			
		Fin Si
		
	Fin Mientras
	Escribir "El Total de calificaciones mayores a 7, es: ", CalMay7 " y el total de calificaciones menor a 7, es: ", CalMen7
FinAlgoritmo


### Ejercicio estatura. 

Realizar programa que calcule el promedio de las estaturas de un determinado número de personas.

1.- Inicio
2.- Promedio<-0
3.- NumPer<-0
4.- Altura<-0
5.- i<-0
6.- Suma<-0
7.- Escribir "¿De cuántas personas quieres saber su altura?"
8.- Leer NumPer
9.-
Mientras i<=NumPer Hacer
i<-i+1
Escribir " Ingresa la altura ", i
Leer Altura
Suma <- Suma + Altura
Promedio<- Suma/NumPer

FinMientras

Escribir "El Promedio de la estatura de estas ", NumPer, " es: ", Promedio 


