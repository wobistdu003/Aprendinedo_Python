
# Operadores aritméticos
Los operadores son elementos de lenguaje que nos permiten realizar cálculos y comparaciones en Python. Aquí hay una lista de los operadores más comunes:
Los operadores aritméticos nos permiten realizar operaciones matemáticas básicas, como la suma, la resta, la multiplicación y la división.

```python
# Suma
print(1 + 2) # 3

# Resta
print(5 - 2) # 3

# Multiplicación
print(3 * 4) # 12

# División
print(10 / 2) # 5.0

# División entera
print(10 // 3) # 3

# Módulo (devuelve el resto de una división)
print(10 % 3) # 1

# Potencia
print(2 ** 3) # 8
```

# Operadores de asignación
Los operadores de asignación nos permiten asignar valores a variables.

```python
x = 10
x += 5 # x = x + 5
print(x) # 15

x -= 3 # x = x - 3
print(x) # 12

x *= 2 # x = x * 2
print(x) # 24

x /= 4 # x = x / 4
print(x) # 6.0

x //= 3 # x = x // 3
print(x) # 2.0

x %= 2 # x = x % 2
print(x) # 0.0

x **= 3 # x = x ** 3
print(x) # 0.0
```

# Operadores de comparación
Los operadores de comparación nos permiten comparar valores y nos devuelven True o False según el resultado de la comparación.

```python
print(1 < 2) # True
print(2 > 1) # True
print(1 <= 2) # True
print(2 >= 1) # True
print(1 != 2) # True
```
Entre estos existen 2 operadores de igualdad, los cuales son == y is.

```python
print(1 == "1") # False
print(1 is "1") # False
```
En el primer caso, 1 == "1" devuelve True ya que solo se está comparando el valor y no el tipo de dato. Sin embargo, en el segundo caso, 1 is "1" devuelve False ya que está comparando tanto el valor como el tipo de dato y, aunque ambos son iguales, uno es de tipo número y el otro de tipo string.

# Operadores lógicos en Python

También tenemos disponibles los operadores lógicos para realizar operaciones de comparación y evaluación.

1.AND (and): Este operador lógico evalúa si ambas expresiones son verdaderas. Si ambas expresiones son verdaderas, devuelve True, de lo contrario, devuelve False. Por ejemplo:

```python
edad = 25
mayor_de_edad = edad >= 18

if edad >= 18 and mayor_de_edad:
    print("Eres mayor de edad")
else:
    print("Aún eres menor de edad")
```
2. OR (or): Este operador lógico evalúa si al menos una de las expresiones es verdadera. Si al menos una de las expresiones es verdadera, devuelve True, de lo contrario, devuelve False. Por ejemplo:

```python
edad = 25
tiene_identificacion = True

if edad >= 18 or tiene_identificacion:
    print("Puedes entrar al bar")
else:
    print("No tienes la edad o la identificación suficiente para entrar al bar")
```

3. NOT (not)**: Este operador lógico invierte el valor de la expresión. Si la expresión es verdadera, devuelve False, de lo contrario, devuelve True. Por ejemplo:

```python
es_fin_de_semana = True

if not es_fin_de_semana:
    print("A trabajar")
else:
    print("A disfrutar del fin de semana")
```
