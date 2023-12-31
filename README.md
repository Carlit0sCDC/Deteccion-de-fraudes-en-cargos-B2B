# Deteccion de fraudes en cargos de mensajeria B2B

Este proyecto utiliza técnicas del lenguaje de programacion Python para agregar una nueva columna en las tablas anteriormente unidas en la cual se compare los cargos esperados en relacion a los cargos demandados por el equipo de mensajeria. Además, se incluye un grafico de torta para entender mas facilmente la proporcion entre los cargos excedentes, faltantes y los cargos correctamente imputados.

## Objetivo

El objetivo principal de este proyecto es implementar tecnicas con pandas para detectar fraudes B2B:

- Comparar cargos y cantidades actuales y esperadas.
- Identificar errores en los cargos provenientes por el equipo de mensajeria B2B.

## Funcionalidades

### 1. Análisis previos y estadisticas

El archivo `desarrollo deteccion de fraudes en cargos B2B.ipynb` incluye la importacion los datos necesarios, la limpieza de los mismos para su posterior utilizacion, la union de diversas tablas para proceder mas eficientemente con la comparacion de cargos, el calculo de los cargos esperados y obtenidos y la visualizacion de proporciones de cargos en un grafico de torta.

### 2. Archivos fuentes

Los archivos `Courier Company - Rates.csv`, `Invoice.csv`, `Order Report.csv`, `pincodes.csv` y `SKU Master.csv`  proveen los datos tabulares para desarrollar el analisis y comparacion posterior.

## Estructura del Proyecto:

- Carga de archivos

- Limpieza de los datos

- Union de datafames y posterior calculo de los cargos

- Visualizacion de la proporcion general de cargos
# Deteccion-de-fraudes-en-cargos-B2B
