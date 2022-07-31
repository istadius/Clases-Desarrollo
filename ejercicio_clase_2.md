# Ejercicio Clase 2

## Objetivo:

Realizar un programa que permita ingresar alumnos y sus notas. Cada alumno debe tener un nombre y una serie de notas que se ingresan todas juntas separadas por comma (pe: 6,8,3).
Es obligatorio que ingrese al menos un alumno con una nota pero debo poder ingresar tantos alumnos y notas como sea necesario.
Las notas son numeros enteros
Luego de ingresar cada alumno con sus notas, el sistema debe preguntarme si deseo ingresar otro alumno mas. Si la respuesta es negativa entonces muestro los datos de finalización.
Los datos de finalización que debo mostrar por consola al terminar de ingresar alumnos son:
- El nombre del alumno con la nota mas alta (y la nota)
- El nombre del alumno con el mejor promedio (y el promedio)
- Un listado con todos los alumnos con su promedio
- El promedio de todos los alumnos (el promedio de los promedios)

## Funciones útiles
- Para dividir el string en un array de strings (notas) pueden usar:
    ```
    string.split(",")
    ```
- Así como vimos el ciclo while tal vez les interese investigar el do while para ir pidiendo los alumnos
- Para el mensaje de confirmación de si desean ingresar otro alumno pueden usar la función: 
    ```
    let resultado : boolean = confirm("¿Desea ingresar otro alumno?")
    ```