## Ejercicio - Random List TDD Python

Realiza pruebas en `unittest` a la función `random_list` que cumpla con lo siguiente:

- Recibe una lista de estudiantes `alumnis`, un número `num` de calificaciones, un valor mínimo `min_value` y un valor máximo `max_value` de calificación.
- Genera de manera automática una lista de `n` calificaciones entre un valor mínimo `min_value` y un valor máximo `max_value` para cada estudiante. 

Escribe un spec para cada una de las siguientes restricciones:

- Is expected List successfully determined to have five sublists with student name & seven grades between 5 and 10?
- Is expected List successfully determined to have four sublists with student name & five grades between 1 and 10?
- Is zero correctly determined not to be valid number of grades? It's important a message when test is failed: `Zero is not valid number for grades number!'`.
- Is zero correctly determined not to be valid min and max grade value? It's important a message when test is failed: `'Zero is not valid number for min and max grade value!'`.
- Is a negative number correctly determined not to be valid? It's important a message when test is failed: `'num, min_value, max_value should not be determined to be valid numbers'`.

Considera el siguiente driver code como ejemplo de salida:

```python
"""driver code"""

print(random_list(["Robert", "Charlis", "Marco", "Pepe", "Angi"], 7, 5, 10))

[['Robert', [5, 8, 5, 7, 5, 9, 8]], ['Charlis', [5, 8, 10, 8, 7, 7, 10]], ['Marco', [9, 5, 10, 8, 8, 5, 8]], ['Pepe', [6, 7, 5, 7, 8, 6, 8]], ['Angi', [7, 6, 7, 8, 9, 7, 7]]]

```

```python
# random_list.py

...


```

```python
# test_random_list.py

...

```

```
#Test Driven Development
$ python3 test_random_list.py

```

> Nota: Para este ejercicio es importante documentarse acerca del uso de `mock` y `patch` en Python:

- [unittest.mock — mock object library]()
- [Getting Started with Mocking in Python](https://semaphoreci.com/community/tutorials/getting-started-with-mocking-in-python).
- [Getting Started with Mock](http://www.voidspace.org.uk/python/mock/getting-started.html).
- [Mocking with Python - Part II](https://kirankoduru.github.io/python/mocking-with-python-part-2.html).


