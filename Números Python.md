# Tipoes de números en Python.

En Python, hay varios tipos de números que puedes usar en tus programas representando valores numéricos. Al mismo tiempo podemos especificar qué tipo de 
dato se espera que tenga una variable, lo que puede ser útil en situaciones donde queremos asegurarnos de que estamos trabajando con el tipo de dato correcto.

Por ejemplo, si queremos que una variable solo pueda contener números enteros, podemos tiparla utilizando el tipo de dato int. De esta forma, Python nos 
mostrará un error si intentamos asignar un número con decimales a esa variable.

```python
edad: int = 30
```
De igual forma, podemos tipar una variable para que solo pueda contener números con decimales utilizando el tipo de dato float

```python
pi: float = 3.14
salario: float = 1500.50
```
También podemos utilizar la notación científica para representar números muy grandes o muy pequeños.

```python
numero_grande = 1e6 # 1 millón
numero_pequeno = 1e-6 # 0.000001
```
### :loudspeaker:
> [!NOTE]
> **Enteros (int)**: Los enteros son números sin parte fraccionaria. Pueden ser positivos o negativos. Algunos ejemplos de enteros son 1, -5, 1000, etc. 
  Python tiene soporte para enteros de tamaño arbitrario, lo que significa que no tienes que preocuparte por desbordamientos de enteros.

> **Números de punto flotante (float)**: Los números de punto flotante representan valores con decimales. Pueden ser números reales positivos o negativos.
  Ejemplos de números de punto flotante son 3.14, -0.001, 2.0, etc.
>**Números complejos (complex)**: Los números complejos son aquellos que tienen una parte real y una parte imaginaria. Pueden ser representados en Python
  usando la notación a + bj, donde a es la parte real y b es la parte imaginaria. Ejemplo: 3 + 2j
