# Proyecto Personal de Métodos Numéricos - Universidad del Valle

Este proyecto fue desarrollado como parte del curso de Métodos Numéricos en la Universidad del Valle. Implementa varios métodos numéricos comunes para la solución de ecuaciones y el análisis estadístico.

## Métodos Implementados

### 1. Método de Newton-Raphson
El **Método de Newton-Raphson** es una técnica iterativa para aproximar las raíces de una función real.

- **Entrada**: El usuario debe proporcionar un valor inicial `x0`.
- **Salida**: Se genera una gráfica de la función y su intersección con el eje `x`, mostrando la raíz aproximada.
- **Tecnologías**: El gráfico es generado usando el paquete **Chart.js**.

#### Ejemplo de uso:
Introduce un valor inicial (por ejemplo, `2`) y presiona "Calcular Raíz". El programa mostrará la aproximación de la raíz y su procedimiento.

### 2. Regresión Lineal: Mínimos Cuadrados
La **Regresión Lineal** utiliza el método de los **mínimos cuadrados** para ajustar una recta a un conjunto de puntos.

- **Entrada**: Los puntos de datos deben ser introducidos en el formato `(x1,y1),(x2,y2),...`.
- **Salida**: La aplicación muestra una gráfica con la línea de regresión que mejor se ajusta a los puntos dados.
- **Tecnologías**: Los resultados son visualizados con **Chart.js**.

#### Ejemplo de uso:
Introduce los puntos en el siguiente formato: `(1,2),(2,3),(3,4)` y presiona "Calcular Regresión" para obtener la línea de ajuste y el procedimiento.

### 3. Método de Bisección
El **Método de Bisección** es una técnica iterativa para encontrar una raíz en un intervalo `[a, b]`.

- **Entrada**: 
  - `f(x)`: Función a evaluar.
  - `a`: Extremo izquierdo del intervalo.
  - `b`: Extremo derecho del intervalo.
  - `T`: Tolerancia (precisión de la raíz).
  - `N`: Número máximo de iteraciones.
  - `milis`: Tiempo de espera entre iteraciones (en milisegundos).
- **Salida**: Se muestra una tabla con los valores de las iteraciones y una aproximación de la raíz.

#### Ejemplo de uso:
Introduce una función como `x^3 + 4x^2 - 10`, establece los valores de `a = 1`, `b = 2`, `T = 0.0001`, `N = 20`, y `milis = 250`, y presiona "Ejecutar" para ver la aproximación de la raíz y la tabla de iteraciones.

## Tecnologías Utilizadas

- **HTML/CSS**: Para la interfaz de usuario.
- **JavaScript**: Para la lógica de los métodos numéricos.
- **Chart.js**: Para las visualizaciones gráficas interactivas.
- **Math.js**: Para funciones matemáticas avanzadas.
- **function-plot.js**: Para graficar funciones matemáticas.
