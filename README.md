# Métodos Numéricos en Python

Repositorio de proyectos académicos desarrollados para la materia de **Métodos Numéricos 2** de la Licenciatura en Matemáticas Aplicadas y Computación en la Facultad de Estudios Superiores Acatlán, UNAM.

El repositorio reúne distintas implementaciones realizadas en Python para aplicar métodos numéricos vistos durante el curso. Como proyecto final, los distintos programas fueron integrados en un mismo paquete para facilitar su ejecución y consulta.

## Contenido

El proyecto incluye implementaciones de los siguientes métodos:

### 1. Método de Broyden

Implementación del método de Broyden para aproximar soluciones de sistemas de ecuaciones no lineales.

El programa trabaja de manera iterativa hasta alcanzar una tolerancia determinada y permite observar el comportamiento de las aproximaciones durante el proceso.

**Conceptos aplicados:**

- Sistemas de ecuaciones no lineales.
- Métodos iterativos.
- Aproximaciones sucesivas.
- Matrices.
- Criterios de convergencia.
- Cálculo y control del error.

---

### 2. Interpolación polinomial por diferencias de Newton

Programa para construir una aproximación polinomial a partir de un conjunto de puntos mediante diferencias de Newton.

Incluye la construcción de tablas de diferencias y la evaluación del polinomio obtenido.

**Conceptos aplicados:**

- Interpolación polinomial.
- Diferencias divididas.
- Diferencias progresivas y regresivas.
- Construcción de tablas de diferencias.
- Evaluación de polinomios.
- Aproximación numérica.

---

### 3. Spline Cúbico Natural

Implementación de interpolación mediante **Spline Cúbico Natural**.

El programa divide el intervalo de datos en distintas regiones y construye un polinomio cúbico para cada una de ellas, manteniendo condiciones de continuidad entre los intervalos.

Incluye diferentes formas de ingresar información, validación de datos y representación gráfica del resultado.

**Funcionalidades principales:**

- Captura manual de puntos.
- Lectura de datos desde archivos CSV.
- Validación y ordenamiento de datos.
- Construcción del sistema de ecuaciones correspondiente.
- Cálculo de los coeficientes de cada polinomio.
- Evaluación del spline.
- Visualización gráfica mediante Python.
- Posibilidad de guardar la gráfica obtenida.

**Conceptos aplicados:**

- Interpolación.
- Splines cúbicos.
- Sistemas de ecuaciones lineales.
- Polinomios por tramos.
- Matrices.
- Visualización de datos.

---

### 4. Integración Numérica

Programa enfocado en la aproximación numérica de integrales mediante diferentes técnicas.

Entre los métodos implementados se encuentran la **regla del trapecio** y la **extrapolación de Romberg**.

**Conceptos aplicados:**

- Integración numérica.
- Regla del trapecio.
- Extrapolación de Romberg.
- Aproximación de integrales.
- Análisis del error.

---

## Paquete Final

Como proyecto final de la materia se desarrolló un programa que integra los distintos métodos estudiados durante el curso.

El paquete permite acceder desde un mismo programa a diferentes herramientas de cálculo numérico, entre ellas:

- Método de Broyden.
- Interpolación por diferencias de Newton.
- Spline Cúbico Natural.
- Integración y aproximación numérica.

El objetivo del proyecto integrador fue reunir las distintas implementaciones realizadas durante el semestre en una sola herramienta y aplicar de manera práctica los conceptos estudiados en la materia.

## Tecnologías utilizadas

- Python
- NumPy
- Matplotlib
- Pandas
- Jupyter Notebook / Google Colab

## Objetivos del proyecto

- Aplicar conceptos matemáticos mediante programación.
- Implementar algoritmos de aproximación numérica.
- Analizar el comportamiento y convergencia de diferentes métodos.
- Trabajar con matrices, funciones, iteraciones y estructuras de datos en Python.
- Integrar diferentes algoritmos en una misma aplicación.
- Utilizar herramientas de visualización para interpretar resultados numéricos.

## Aprendizajes

El desarrollo de estos programas permitió aplicar conceptos matemáticos vistos durante el curso y relacionarlos con programación.

El proyecto también permitió reforzar habilidades relacionadas con:

- Programación en Python.
- Desarrollo de algoritmos.
- Resolución numérica de problemas matemáticos.
- Manejo de matrices y datos.
- Validación de entradas.
- Interpretación de resultados.
- Organización de programas con distintas funcionalidades.

## Trabajo en equipo

Todos los programas individuales y el paquete final fueron desarrollados en colaboración.

El trabajo incluyó investigación de los métodos numéricos, implementación en Python, validación de resultados, pruebas y organización de los distintos programas dentro del paquete final.

## Integrantes

- **Luis Alberto Avendaño Zarza**
- **Williams Islas Hernández**

## Contexto académico

Proyecto realizado con fines académicos como parte de la materia de **Métodos Numéricos 2** de la Licenciatura en Matemáticas Aplicadas y Computación.

Los programas fueron desarrollados durante distintas unidades del curso y posteriormente integrados en un paquete final.
