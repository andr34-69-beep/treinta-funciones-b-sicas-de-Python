# treinta funciones basicas de Pyhon
este es un repositorio para investigar y documentar, al menos, treinta funciones básicas de Python, explicando su uso y proporcionando ejemplos prácticos.
Cada función incluye descripción, utilidad, ejemplo ejecutable e interpretación del resultado.

## Objetivo
Reconocer y aplicar funciones básicas de Python para trabajar con datos, realizar operaciones y manipular colecciones.

## Contenido
- `notebooks/30_Funciones_Basicas_Python.ipynb`: cuaderno Jupyter con la investigación y los ejemplos.

## Requisitos
- Python 3.
- Jupyter Notebook o JupyterLab.

## Integrantes
- Integrante 1: Laura Beltran
- Integrante 2: Camilo Sanchez
- Integrante 3: Andrea Riaño


Funciones 20 - 30
## 20. Función `map()`

**¿Qué hace?** Aplica una función a cada elemento de un iterable y devuelve un iterador con los resultados.

**Sintaxis general:** `map()`


**Ejemplo práctico:**
precios = [1000, 2000, 3000]
precios_con_iva = list(map(lambda precio: precio * 1.19, precios))
print(precios_con_iva)
