Hacer un programa que solicite cualquier numero, y realice la multiplicación de ese número hasta 10. Ademas, realizar las tablas de myultiplicar del 1 al 10, usando for(for).

ALGORITMO: 
P1.- Inicio.
P2.- Declarar (i, Num, Multiplicar) int
P3.- Asignar (i==1)
P4.- Mostrar ("Ingresa cualquier número, para realizar su tabla de multiplicar")
P5.- Asignar (Num)
P6.- PARA(i<=10) HACER 
  Multiplicar=Num*i 
   Mostrar (Multiplicar)
   i=i++
   FIN PARA

Algoritmo MULTIPLICACIÓN
	Escribir "Ingresa cualquier número, para realizar su tabla de multiplicar"
	Leer Num
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		Multiplicar<-Num * i
		Escribir Num," * ",i," = ",milti
	Fin Para
FinAlgoritmo
