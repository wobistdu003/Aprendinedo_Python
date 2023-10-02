# Definiendo una función tipo (type). 

Este código define una función llamada **found_type**. Esta función toma un argumento llamado (value) que verifica su tipo y luego imprime un mensaje en función de el mismo. 
En consola imprimira los mensajes segun el tipo que le pase como argumento cuando se llama la función.

```python
def found_type(value):
   if type(value) == int:
      print("number")
   elif type(value) == str:
      print ("string")
   else:
      print ("Boolean")

found_type(1)
found_type("Dieguillo")
found_type(True)
```
A continuación se hace una breve descripcion de l funcionamiento del codigo:

1. Se define una función llamada (found_type) que toma un argumento llamado (value).
2. Dentro de la función, se utilizan declaraciones if, elif y else para verificar el tipo de valor (value) usando la función type().
3. Si value es de tipo **int**, se ejecuta print("number").
4. Si value es de tipo **str**, se ejecuta print("string").
5. Si value es de tipo **boll**, se ejecuta print("Boolean").
6. Luego, se llama a la función found_type tres veces con diferentes valores: 1, "Dieguillo", y True. Cada vez que se llama a la función,
   imprimirá el mensaje correspondiente según el tipo del valor que toma.
