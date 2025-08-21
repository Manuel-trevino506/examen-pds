# examen-pds

## Tarea 1 - Graficación de señales continuas y discretas

*Nombre del alumno:* Evian Manuel Treviño Flores  
*Fecha:* 31 de mayo de 2025

---

## 🎯 Objetivos

El objetivo de esta tarea es representar gráficamente diferentes tipos de señales, tanto en su forma continua como discretizada. Las señales a graficar son:

- Una señal sinusoidal de frecuencia \( f = 2 \) Hz
- Una señal exponencial decreciente con escalón unitario
- Una señal triangular periódica
- Una señal cuadrada periódica

---

## 🧠 Descripción del proceso

Para cada señal se definió un intervalo de tiempo \( t \in [-1, 5] \) con al menos 1000 puntos para obtener una gráfica suave en la versión continua. Luego se definió un periodo de muestreo \( T_s = 0.01 \) s para obtener la versión discreta, la cual se superpuso sobre la señal continua.

---

## 🔧 Librerías utilizadas

- numpy para cálculos y generación de señales
- matplotlib para graficación
- scipy.signal para generar señales periódicas

---

## 🖼 Gráficas

Las gráficas se encuentran en la figura generada por el script tarea1.py, con cada señal en su propio subplot para facilitar su análisis visual.

---

## 🔗 Repositorio base

Este proyecto se basa en el repositorio original:  
https://github.com/CharlyMercury/pds_upv

---

## Uso

1. Clonar el repositorio  
2. Ejecutar el script tarea1.py en un entorno con Python y las librerías necesarias instaladas  
3. Visualizar las gráficas generadas para cada tipo de señal continua y discreta 
