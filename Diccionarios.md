# Diccionarios Python.

En Python, un diccionario es una estructura de datos que permite almacenar y organizar datos de manera flexible. Se trata de una colección 
de pares clave-valor, donde cada valor está asociado a una clave única. Los diccionarios son muy útiles cuando necesitas acceder y manipular 
datos utilizando una clave en lugar de un índice numérico, como lo harías en una lista o una tupla.

Para crear un diccionario, debemos utilizar las llaves {} y especificar los elementos del diccionario mediante la sintaxis clave: valor. Los valores 
de los elementos pueden ser de cualquier tipo de dato, incluyendo otros diccionarios.


```python
persona = {
  "nombre": "Juanita",
  "Año": 2023,
	"Familiares": {
		"nombre": "Andres F",
		"Edad": 20,
		"Parentesco": "Primo"
	}
}
```
Para acceder a los elementos de un diccionario, podemos utilizar la clave como índice.

```python
print(persona["nombre"]) # "Juanita"
print(persona["Familiares"]["nombre"]) # "Andres F"
print(persona"Familiares"]["Edad"]) # 20
print(persona["Año"]) # 2023
	}
}
```
