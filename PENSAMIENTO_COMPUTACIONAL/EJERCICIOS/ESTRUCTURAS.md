# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo.

* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

ALGORITMO:
    
P1: Inicio.

P2: Declarar variable (letra) char.

P3: Mostrar "Ingresar letra".

P4: Asignar letra. 

P5: 
Si letra==s o letra==n.
    
  Mostrar "Carácter permitido"
    
SiNo 
    
  Escribir "Carácter no permitido"
    
FinSi

P7: Fin.

DIAGRAMA:
* ![image](https://user-images.githubusercontent.com/103280092/164296008-de740936-dca7-4f47-bf83-84531728c8f3.png)


* Un programa que pida una letra y detecte si es una vocal.

ALGORITMO:

P1.- Inicio Proceso.

P2.- Declarar variable (Letra) char.

P3.- Mostrar "Ingrese alguna letra para detectar si es vocal.

P4.- Asignar Letra

P5.- 
En Caso de (Letra) Hacer:

 Caso "a" o "A": Mostrar "Es una Vocal"
 Caso "e" o "E": Mostrar "Es una Vocal"
 Caso "i" o "I": Mostrar "Es una Vocal"
 Caso "o" o "O": Mostrar "Es una Vocal"
 Caso "u" o "U": Mostrar "Es una Vocal"

De otro Modo: Mostrar "Es una consonante"

FinCaso

P6.- Fin Proceso.

DIAGRAMA: 

* ![image](https://user-images.githubusercontent.com/103280092/164540107-13f31846-f786-4542-9adc-f29e96c221ce.png)



* Programa que pida 3 números y los muestre en pantalla de menor a mayor.
    
ALGORITMO:
    
P1: Inicio.

P2: Declarar variables (Num1, Num2, Num3) int or float.

P3: Mostrar "Ingresar 3 números".

P4: Asignar Num1.

P5: Mostrar Num1.

P6: Asignar Num2.

P7: Mostrar Num2.

P8: Asignar Num3.

P9: Mostrar Num3.

P10:

Si Num1<Num2 y Num1<Num3

  Si Num2<Num3

  Mostrar Num1, Num2, Num3.

SiNo

  Mostrar Num1, Num3, Num2.

FinSi.

SiNo

Si Num2<Num1 y Num2<Num3

  Si Num1<Num3

  Mostrar Num2, Num1, Num3.

SiNo

  Mostrar Num2, Num3, Num1.

FinSi.

SiNo

Si Num3<Num1 y Num3<Num2

  Si Num1<Num2

  Mostrar Num3, Num1, Num2.

SiNo

  Mostrar Num3, Num2, Num1.

FinSi

FinSi.

P11: Fin.
     
DIAGRAMA:

* ![image](https://user-images.githubusercontent.com/103280092/164313907-e24f5f9c-dbc4-493d-bb3e-cb162e2b390c.png)

* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

ALGORITMO:

P1.- Inicio Proceso.

P2.- Declarar variable (Mes) int.

P3.- Mostrar ("Ingrese número para mostrar el mes que le corresponde")

P4.- Asignar (Mes) int.

P5.- 

En Caso (Mes) Haga
    Caso 1: Mostrar ("Enero")
    Caso 2: Mostrar ("Febrero")
    Caso 3: Mostrar ("Marzo")
    Caso 4: Mostrar ("Abril")
    Caso 5: Mostrar ("Mayo")
    Caso 6: Mostrar ("Junio")
    Caso 7: Mostrar ("Julio")
    Caso 8: Mostrar ("Agosto")
    Caso 9: Mostrar ("Septiembre")
    Caso 10: Mostrar ("Octubre")
    Caso 11: Mostrar ("Noviembre")
    Caso 12: Mostrar ("Diciembre")

SiNo
    Mostrar ("Este es un número fuera del rango asignado")

FinCaso.

P6.- Fin Proceso

DIAGRAMA:

* ![image](https://user-images.githubusercontent.com/103280092/164529449-a27a664b-7e98-4a65-b65e-17d77201b63d.png)


* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.
* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
