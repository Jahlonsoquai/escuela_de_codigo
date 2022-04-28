### Ejercicios.

* Realizar el promedio de un determinado número de calificaciones, y cuando el usuario presione 0, el ciclo se rompa.

1.- Inicio

2.- i<-0

3.- Suma<-0

4.- Media<-0

5.- Num<-0

6.-

Repetir
i<-i+1
Escribir ("Ingresa el número")
Leer Num
Suma<-Suma+Num
Media<-Suma/i
Mientras (Num=0)

FinHacerMientras
Escribir ("El Promedio es: ", Media )
Fin.

* Realizar un programa para pedir al usuario que ingrese un numero de entre el 0 al 999 y con base al numero que ingrese,  que le diga al usuario, de cuantas cifras es el número que ingreso. 
Y cuando el usuario ingrese 0 el ciclo se rompa.

* ALGORITMO.

1.- Inicio.

2.- Num<-0

3.-
Repetir
  Escribir ("Ingresa algún número del 0 al 999, para declarar de cuántos digitos es")
  Leer Num.
Si Num>0 y Num<=999 Entonces
  Si Num>0 y Num<=9
  Escribir ("El número es de 1 digito")
   SiNo
   Si Num>=10 y Num<=99 Entonces
    Escribir ("El número es de 2 digitos")
       
SiNo
Escribir ("Número no permitido")
FinSi
  FinSi
   SiNo
        Escribir("El número es de 3 digitos)
    FinSi
Mientras o Hasta que Num=0

* En PSeInt
Algoritmo CalcCifrasNúmero
	
  Repetir
		Escribir "Ingresa algún número del 0 al 999, para declarar de cuántos digitos es"
		Leer Num
		
		Si Num>0 y Num<=999 Entonces
			Si Num>0 y Num<=9 Entonces
				Escribir "El número es de 1 digito"
			SiNo
				
				Si Num>=10 y Num<=99 Entonces
					Escribir "El número es de 2 digitos"
				SiNo
					Escribir "El número es de 3 digitos"
					
				FinSi
			FinSi
		SiNo
			Escribir "Número inválido"
		FinSi
	Hasta Que Num=0
	
FinAlgoritmo

* Otra Forma
Algoritmo CifrasdeNúmeros
	Num<-0
	Repetir
		Escribir "Ingresa un número entre 0 y 999"
		Leer Num
		Si Num>0 y Num<=999 Entonces
			Si Num>100 Entonces
				Escribir "Tú número tiene 3 digitos"
			SiNo
				Si Num>10 Entonces
					Escribir " Tu número tiene 2 digitos"
				SiNo
				Escribir "Tu número tiene 1 digito"
				Fin Si
			Fin Si
		SiNo
			Escribir "Número fuera de rango"
		Fin Si
	Hasta Que Num=0
FinAlgoritmo

