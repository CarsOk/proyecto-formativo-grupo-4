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

> 

# Ejercicio 3. CICLO MIENTRAS

> 

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

Hasta que peso>1


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