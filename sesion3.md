<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->


Actividad: Repositorio local de ejercicios de estructuras de control iterativas. (Trabajo individual)
Crea un repositorio local y resuelve los siguientes ejercicios para practicar bucles while y for:

Ejercicios con bucle while:

Solicita al usuario que ingrese una lista de números y encuentra el número mayor y el menor.
Solicita al usuario un número e imprime la suma de los números pares entre 1 y ese número.
Solicita al usuario una cadena e imprime cuántas vocales contiene.
Solicita al usuario un número y muestra su tabla de potencias desde 1 hasta 10.
Solicita al usuario una lista de números y calcula la media aritmética.
Ejercicios con bucle for:

Solicita al usuario una lista de números y calcula la suma de sus elementos.
Solicita al usuario una lista de números e imprime cuántos de ellos son pares.
Solicita al usuario un número y muestra su tabla de multiplicar usando range().
Solicita al usuario un número e imprime los números pares desde 2 hasta ese número.
Solicita al usuario un número y muestra la secuencia de números pares desde 2 hasta ese número.
Acciones en el repositorio local:

Captura de pantalla de la configuración inicial del repositorio.
Hacer commit por cada ejercicio.
Captura de pantalla del comando git log.
Captura de pantalla del comando git diff.
Nota: Incluir las captura de pantalla en el repositorio local.








https://colab.research.google.com/drive/1RRKbSqwGum_hHmWe848vzQDrknKL5-ty?usp=sharing#scrollTo=kRzrAIElTr59


```python 
numeros = [1, 2, 3, 4, 5, 5, 6, 7, 8, 9, 10]
print(numeros)
numeros.sort()
print(numeros)
numeros.sort(reverse=True)
print(numeros)
numero_menor = min(numeros)
print("El número más pequeño en la lista es:", numero_menor)
numero_mayor = max(numeros)
print("El número más grande en la lista es:", numero_mayor)
numero_a_contar = 5
cantidad = numeros.count(numero_a_contar)
print(f"El número {numero_a_contar} aparece {cantidad} veces en la lista.")
numero_a_eliminar = 5
while numero_a_eliminar in numeros:
    numeros.remove(numero_a_eliminar)
print("Lista después de eliminar el número", numero_a_eliminar, ":", numeros)
numero_a_agregar = 11
numeros.extend([numero_a_agregar])
numero_a_agregar = 11
print("Lista después de agregar el número", numero_a_agregar, ":", numeros)
numeros.sort()
print("Lista actualizada en orden:", numeros)
```




