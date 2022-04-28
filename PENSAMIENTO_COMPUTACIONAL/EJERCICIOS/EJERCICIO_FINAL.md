### Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

#### En PSeInt, existe la función azar que generar un número aleatoriamente

1.- InicioAlgoritmo

2.- NumSecr<-azar(100)+1

3.- Num<-0

4.- i<-10

5.- 

Escribir "Adivina el número"

Leer Num

Mientras Num<>NumSecr y i>0 Hacer
i=i-1

Mientras Num<0 o Num>100 Hacer

Escribir "Número fuera del rango asignado"

Escribir  "Ingresa otro número del 0 al 99"

Leer Num

FinMientras

Si Num>=0 y Num<=100 Entonces

Si Num>NumSecr Entonces

Escribir "El número es mayor"

SiNo Escribir "El número es menor"

FinSi

FinSi

Escribir "Te quedan ", i " intentos. Ingresa otro número"

Leer Num

Fin Mientras

j<-0

j=j+i

Si Num=NumSecr Entonces

Escribir "Felicidades adivinaste en ", j, " intentos."

SiNo 

Escribir "Se terminaron tus oportunidades, el número era ", NumSecr, "Surte para la próxima"

FinSi

6.- FInAlgoritmo
  
    Algoritmo ADIVINAunNUM
    NumSecr<-azar(100)+1
    Num<-0
    i<-10
    Escribir "Adivina el número"
    Leer Num
    Mientras Num<>NumSecr y i>0 Hacer
      i=i-1

		Mientras Num<0 o Num>100 Hacer
			Escribir "Número fuera del rango asignado"
			Escribir  "Ingresa otro número del 0 al 99"
			Leer Num
		FinMientras
		
		Si Num>=0 y Num<=100 Entonces
					
		Si Num>NumSecr Entonces
			Escribir "El número es mayor"
		SiNo
			Escribir "El número es menor"
		Fin Si
	
	FinSi
	
		Escribir "Te quedan ", i, " intentos"
		Escribir "Ingresa otro número"
		Leer Num
		
	Fin Mientras
	
	j<-0
	j=j+i
	
		Si Num=NumSecr Entonces
			Escribir "Felicidades adivinaste en ", j, " intentos."
		SiNo 
			Escribir "Se terminaron tus oportunidades, el número era ", NumSecr, " Suerte para la próxima"
		FinSi
				
	FinAlgoritmo

 
Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
