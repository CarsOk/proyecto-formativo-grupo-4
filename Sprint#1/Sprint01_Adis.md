# Ejemplo 1. CONDICIONALES

>Determine el mayor valor de 5 números

Algoritmo

Escribir"Ingrese primer número"

Leer"num1"

Escribir"Ingrese el segundo número"

Leer"num2"

Escribir"Ingrese el tercer número"

Leer"num3"

Escribir"Ingrese cuarto número"

Leer"num4"

Escribir"Ingrese quinto número"

Leer"num5"

nm=num1

Si nm<num2 Entonces

nm=num2

FinSi

Si nm<num3 Entonces

nm=num3

FinSi

Si nm<num4 Entonces

nm=num4

FinSi

Si nm<num5 Entonces

nm=num5

FinSi

Escribir"EL mayor numeros es: " nm

FinAlgoritmo

# Ejercicio 2. CICLO PARA

>Una compañía tiene una fórmula poco común para calcular el sueldo de sus empleados. El sueldo semanal para un empleado es igual a:

$ 100+ $(edad del empleado) + ($ 1+ 2+ 3+...+ años en la compañía)

Así, si un empleado de 37 años de edad tiene una antigüedad de seis años, ganaría el sueldo semanal de $ 158, ya que es la suma de 100 + 37 (edad) + 21, en donde 21 es la suma de 1+2+3+4+5+6. Escriba un algoritmo para calcular el pago quincenal de un empleado, recibiendo como entrada la edad y los años que lleva en la compañía.

Algoritmo

Escribir"Ingrese su edad"

Leer edad

Escribir"Ingrese años en la compañia"

Leer Añoscomp

suma=0

pares P=1 hasta Añocomp con paso 1 hacer

Suma=suma+1

Finpara

Escribir Su Sueldo quincenal es de", (100+edad+suma)*2

FinAlgoritmo

# Ejercicio 3. CICLO MIENTRAS

> Realizar un algoritmo que imprima los 25 primeros terminos de la serie (11, 22, 33, 44, 55 ....)}

Algoritmo
 a=0

mientras a≠25 hacer

a=a+1

Escribir a a

Fin mientras

Fin 


# Ejercicio 4. CICLO REPETIR

> Una veterinaria requiere comprar la cantidad exacta de alimento para perros que tiene a su cuidado. La idea es que no falte alimento, por lo cual se determina según el seguiente criterio.

|TAMAÑO|PESO|GRAMOS|
|-------|------|------|
|Miniatura|1 a 4 kilos|50 a 150|
|Pequeña|5 a 15 kilos|200 a 360|
|Mediana|16 a 29 kilos|420 a 700|
|Grande|30 a 50 kilos|800 a 1260|
|Muy Grande|51 o más kilos|1500 a 1750|

- Debe solicitar al inicio la cantidad de animales existentes en la veterinaria.

El programa debe entregar:

+El total de animales que son grandes y muy grandes.
+La cantidad de animales que pesan mas de 25 kilos
+El promedio de gramos que comen los perros

Ademas, deben validar:
+La cantidad de peso de un perro debe ser mayor igual a 1
+La cantidad de gramos deb ser superior a 50g

Algoritmo

cont=0
contg=0
contmg=0
contp=0

Escribir"¿Cuantos animales hay en la veterinaria?"

leer contaminales


Repetir

cont=cont+1

Escribir"Ingresa tamaño para animales, " cont

Escribir"Miniatura, Pequeña, Mediana, Grande, Muy grande"

Leer tamagno


Repetir 

Escribir"Ingresa peso para animal " cont

leer peso

Hasta que peso>=1


Repetir

Escribir"Ingrese cantidad de gramos que come el perro " cont
Escribir"Recuerde que los gramos deben ser superior a 50"

Leer gramos

Hasta que gramos>50

acumular=acumular+gramos

Si peso>25 Entonces

contp=contp+1

Finsi

Si tamaño=="grande" entonces

contg=contg+1

sino

Si tamaño=="muy grande" entonces

contmg=contmg+1

Finsi

Finsi

Hasta Que cont==cantanimales

Promgramos=acumular/cont

FinAlgoritmo

Escribir"Existen ",contg," animales grandes"

Escribir"Existen ",contmg," animales muy grandes"

Escribir"Existen ",contp," animales con peso sobre los 25 kilos"

Escribir"El promedio de gramos que comen los perros son ",promgramos,"gramos"

# Ejercicio 5. Selector Multiple

>  