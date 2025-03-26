# Manejo de Excepciones y Funciones Lambda en Python

Este repositorio contiene dos archivos `ipynb` que abordan dos conceptos fundamentales de Python: el manejo de excepciones utilizando los bloques `try`, `except`, `else` y `finally`, y las funciones `lambda`.

## Manejo de Excepciones en Python

En Python, los bloques `try`, `except`, `else` y `finally` son herramientas esenciales para manejar errores y excepciones en tu código. A continuación se explica cada uno de estos bloques:

- **`try`**:  
  Se utiliza para envolver el código que podría generar una excepción. Si ocurre un error dentro del bloque `try`, la ejecución se transfiere al bloque `except`.
  
- **`except`**:  
  El bloque `except` se utiliza para manejar la excepción que ocurrió en el bloque `try`. Puedes tener varios bloques `except` para manejar diferentes tipos de excepciones.

- **`else`**:  
  El bloque `else` se ejecuta solo si no se produce ninguna excepción en el bloque `try`. Es útil para ejecutar código cuando el bloque `try` se completa con éxito.

- **`finally`**:  
  El bloque `finally` se ejecuta siempre, sin importar si hubo una excepción o no. Generalmente se utiliza para limpiar recursos, como cerrar archivos o conexiones.

Los conceptos de manejo de excepciones permiten hacer que el programa sea más robusto y predecible, gestionando errores de manera eficaz y asegurando que ciertos procesos se realicen siempre.

Puedes encontrar ejemplos y explicaciones de estos bloques en el archivo `Manejo_de_Excepciones.ipynb`.

## Funciones Lambda en Python

Las funciones `lambda` en Python permiten definir funciones pequeñas y anónimas en una sola línea. La sintaxis básica es:

```python
lambda argumentos: expresión
```
Las funciones lambda son especialmente útiles cuando necesitas una función simple para ser utilizada en el contexto de otra función, como con map(), filter() o sorted().

Por ejemplo, una función lambda puede ser utilizada para sumar dos números:

```python
suma = lambda a, b: a + b
print(suma(5, 3))  # Salida: 8
```

## 🚀 Cómo Usar Este Repositorio

1. **Clona el repositorio** en tu máquina:
   ```bash
   git clone (https://github.com/gabykap29/tlp3_py_introduction.git)
   ```
2. **Abre Visual Studio Code con la extension instalada de Jupiter Notebook** y explora los ejemplos:
   ```bash
   code .
   ```
3. **Selecciona el notebook (`.ipynb`) que desees ejecutar** y sigue las instrucciones dentro de cada celda.

## 🛠 Requisitos

Para ejecutar los ejemplos, necesitas:
- **Python 3.x** (verifica tu versión con `python --version` o `python3 --version`).
- **Extension de VSCODE: jupack(pack de extensiones para jupiter notebook) o la extension oficial** 




