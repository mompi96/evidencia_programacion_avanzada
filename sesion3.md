<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->


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




