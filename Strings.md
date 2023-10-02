# Strings Python.

Los "strings" (cadenas de texto) en Python son secuencias de caracteres, es decir, una colección ordenada de caracteres que representan texto. 
Los strings se utilizan para representar y manipular texto en Python.

Podemos representar el texto mediante los strings en Python encerrando el texto entre comillas simples (') o comillas dobles ("). Por ejemplo:
   
```python
cadena_1 = 'Hola, mundo!'
cadena_2 = "Python es genial
```
Asi mismo, los strings pueden ser tipados para evitar errores a futuro.

```python
cadena_1: str = "Hola, ¿cómo estás?"
```

Igualmente, se puede unir o concatenar strings utilizando el operador "+". Esto simplemente fusiona dos o más strings en uno solo.

```python
print("Hola, " + nombre + " " + apellido + "!") 
# "Hola, Hola, mundo! Python es genial"
```
También podemos utilizar la notación f-strings para crear strings que incluyen variables y expresiones:

```python
print(f"Hola, {cadena_1} {cadena_2}!") 
# "Hola, mundo! Python es genial"
```

Python proporciona una serie de métodos para manipular strings. Algunos de los métodos más comunes son:

```python
Pais = "Colombia"

print(len(nombre)) # 8
print(nombre.upper()) # COLOMBIA
print(nombre.lower()) # colombia
print(nombre.split('m')) # ['Colo', 'bia']
```
