# Strings Python.

En Python, los valores booleanos son un tipo de dato que se utiliza para representar dos estados: verdadero (True) y falso (False). Los valores 
booleanos se utilizan comúnmente en expresiones lógicas y de control de flujo para tomar decisiones en programas.

```python
cadena_1 = True
cadena_2 = False
```

Los valores booleanos se obtienen a menudo al comparar dos valores utilizando operadores de comparación como == (igual a), != (diferente de),
< (menor que), > (mayor que), <= (menor o igual que) y >= (mayor o igual que). Por 

```python
x = 5
y = 10
resultado = x < y
# Esto dará como resultado True porque 5 es menor que 10
```
Los valores booleanos también se utilizan en operaciones lógicas utilizando operadores como and (y), or (o) y not (no). Estos operadores permiten
combinar y evaluar múltiples expresiones booleanas. 

```python
a = True
b = False
# Esto dará como resultado False porque ambas condiciones deben ser verdaderas
resultado_and = a and b  
# Esto dará como resultado True porque al menos una condición debe ser verdadera
resultado_or = a or b    
# Esto dará como resultado False porque not invierte el valor booleano
resultado_not = not a    
```

 Los valores booleanos se utilizan en estructuras de control de flujo, como las instrucciones if, elif y else, para tomar decisiones basadas en condiciones lógicas.
 
```python
x = 42
if x > 50:
    print("x es mayor que 50")
else:
    print("x no es mayor que 50")   
```


Los valores booleanos se utilizan a menudo como valores predeterminados en funciones para permitir a los usuarios especificar si desean habilitar o deshabilitar 
ciertas características.

```python
def procesar_datos(datos, modo_debug=False):
    if modo_debug:
        print("Modo debug habilitado")
    # Realizar procesamiento de datos
```

Asi mismo si no se recuerda el tipo de dato con el que estamos trabajando, existe dentro de python la funcion **type*()** la cual nos dira el tipo de datos con el que estamos trabajando.

```python
type("Fundamentos_Python") 
# <class 'str'>
type(10) 
# <class 'int'>
type({}) 
# <class 'dict'>

type([]) # <class 'list'>
```
* type("Fundamentos_Python") devuelve <class 'str'>, lo que significa que "Fundamentos_Python" es una cadena de texto (string).
* type(30) devuelve <class 'int'>, lo que significa que 30 es un número entero (integer).
* type({}) devuelve <class 'dict'>, lo que significa que {} es un diccionario.
* type([]) devuelve <class 'list'>, lo que significa que [] es una lista.

