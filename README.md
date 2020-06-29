#### Inteligencia Artificial
# Maquinas de Boltzmann Restringidas (RBM)

El presente trabajo muestra la implementación de 
las Máquinas de Boltzmann Restringidas (RBM).

## Fuentes:
- Repositorio: https://github.com/jaquino/ia_rbm
- Preview: https://jaquino.github.io/ia_rbm/
- Datasets:
    - https://grouplens.org/datasets/movielens/100k/
    - https://grouplens.org/datasets/movielens/1m/

## Herramientas
- Lenguaje de programción: Python 3.8.x
- Framework de trabajo: Jupyter lab 2.1.x

## Librerías
- NumPy
- Pandas
- Torch

## Datasets
- ml-1m
    - movies.dat
    - users.dat
    - ratings.dat
- Entrenamiento y Testing (ml-100k)
    - u1.base
    - u1.test

## Script
- Importando librerías
- Preparar el conjunto de entrenamiento y elconjunto de testing
- Convertir los datos en una matriz bidimensional X[u,i] con usuarios u en fila y películas i en columnas
- Convertir los datos a tensores de Torch
- Convertir las valoraciones a valores binarios 1 (Me gusta) o 0 (No me gusta)
- Crear la arquitectura de la Red Neuronal (clase RBM)
- Entrenar la RBM
- Testear la RBM
