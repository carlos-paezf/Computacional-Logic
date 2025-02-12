# Pruebas de escritorio

## ¿Qué es una prueba de escritorio?

Las pruebas de escritorio (también conocidas como "pruebas en seco" o "dry run") son una técnica utilizada en la programación para verificar el correcto funcionamiento de un algoritmo antes de ejecutarlo en un entorno real. Consisten en simular la ejecución del código línea a línea, registrando manualmente los valores de las variables en cada paso.

Esta técnica es útil para:

- ***Detectar*** errores lógicos antes de compilar o ejecutar el programa
- ***Comprender*** cómo se comporta un algoritmo en diferentes escenarios
- ***Verificar*** la lógica de control de flujo y estructuras de datos utilizadas

## Objetivos de las pruebas de escritorio

Detectar errores en la lógica del programa sin necesidad de ejecutarlo.
Comprender el flujo de ejecución, especialmente en estructuras de control.
Mejorar la depuración y comprensión del código.
Pasos para realizar una prueba de escritorio
Leer y analizar el código para comprender su estructura.
Identificar las variables y su valor inicial.
Simular la ejecución, línea por línea, registrando los cambios en las variables.
Validar la salida esperada comparándola con la calculada manualmente.

## Pasos para realizar una prueba de escritorio

1. Definir el algoritmo o código a evaluar
2. Seleccionar valores de entrada representativos
3. Crear una tabla de seguimiento de variables
4. Ejecutar manualmente cada instrucción, registrando los cambios en la tabla
5. Comprar el resultado obtenido con el esperado
6. Identificar posibles errores y realizar correcciones si es necesario

## Ejemplo 01

*Enunciado*: Crear un algoritmo que determine si un número es positivo, negativo o cero.

*Solución en pseudocódigo:*

```py
def suma_hasta_n(n):
    suma = 0
    for i in range(1, n + 1):
        suma += i
    return suma

resultado = suma_hasta_n(5)
print(resultado)  # Salida esperada: 15
```

*Prueba de escritorio:*

|Iteración|i|suma|
|Inicial|-|0|
|1|1|1|
|2|2|3|
|3|3|6|
|4|4|10|
|5|5|15|

Al final, suma_hasta_n(5) devuelve 15, lo que confirma que el código es correcto.

## Preguntate

- ¿Cuál es el propósito de una prueba de escritorio?
- ¿Cómo se realiza una prueba de escritorio para un bucle while?
- ¿Qué beneficios tiene hacer una prueba de escritorio antes de ejecutar un programa?
- ¿Se pueden detectar todos los errores con pruebas de escritorio? ¿Por qué?
- ¿Cómo se representan los valores de las variables en una prueba de escritorio?

## Aplicación práctica

Las pruebas de escritorio son útiles en:

- *Depuración de código:* Detectar errores lógicos antes de ejecutar el programa.
- *Análisis de algoritmos*: Validar que un algoritmo funcione antes de implementarlo.
- *Enseñanza de programación*: Facilitar la comprensión del flujo de ejecución.
- *Optimización de código*: Identificar ineficiencias en algoritmos.

## Ejemplo práctico:

Antes de ejecutar un algoritmo de ordenamiento, se puede hacer una prueba de escritorio para verificar su comportamiento con diferentes listas de entrada.

## Bibliografía

- Kernighan, B. W., & Ritchie, D. M. (1988). *The C Programming Language*. Prentice Hall.
- Zelle, J. (2017). *Python Programming: An Introduction to Computer Science*. Franklin, Beedle & Associates.
- McConnell, S. (2004). *Code Complete: A Practical Handbook of Software Construction.* Microsoft Press.
- Downey, A. (2012). *Think Python: How to Think Like a Computer Scientist*. O'Reilly Media.

|Anterior||Siguiente|
| --- | --- | --- |
|[Algoritmos, Pseudocódigo y Diagramas de Flujo](03-Algoritmos_Pseudocodigo_y_Diagramas_de_flujo.md)|[README](../README.md)|[]()|
