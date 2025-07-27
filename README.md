# Prácticas de la asignatura Visión por Computador Aplicada

Este repositorio contiene las prácticas desarrolladas en el contexto de la asignatura **Visión por Computador Aplicada**, centradas en la aplicación de técnicas de aprendizaje profundo a tareas reales de detección y segmentación de imágenes.

## Práctica 1: Detección de barcos

### Parte 1: Detección de presencia de barcos en el puerto

Se ha utilizado un conjunto de imágenes reales obtenidas de una cámara de vigilancia ubicada en un puerto durante varios días. Las imágenes están acompañadas por un archivo de anotaciones (`ship.csv`) que indica si un barco es visible en cada imagen.

Para esta tarea se ha entrenado un modelo basado en la arquitectura **RegNet**, adaptado al problema de clasificación binaria, con el objetivo de predecir la presencia o ausencia de un barco en la escena.

### Parte 2: Detección de barcos atracados

En esta segunda parte se ha trabajado con otro conjunto de imágenes del mismo entorno, etiquetadas mediante el archivo `docked.csv` para indicar si el barco se encuentra atracado o no.

Se ha desarrollado un segundo modelo, también basado en **RegNet**, con el fin de abordar esta nueva tarea de clasificación.

Los resultados obtenidos, junto con su análisis e interpretación, se presentan en el informe correspondiente:  
**`P1_memoria.pdf`**

## Práctica 2: Segmentación de imágenes retinoculares

En esta práctica se ha trabajado con un conjunto de imágenes retinoculares reales, acompañado de sus respectivas máscaras de segmentación proporcionadas por expertos. Estas máscaras delimitan regiones de interés en las retinas, y han sido anonimizadas conforme a la normativa vigente (sin datos personales, aunque se conservan algunas marcas del software médico utilizado).

Para la tarea de segmentación se ha empleado un modelo **U-Net**, explorando el impacto de distintas funciones de pérdida y técnicas de regularización sobre el rendimiento del modelo.

El desarrollo, los resultados y las conclusiones de esta práctica se encuentran documentados en el informe:  
**`P2_memoria.pdf`**


## Autoría


Trabajo realizado en el marco de la asignatura **Visión por Computador Aplicada**, del Grado en Inteligencia Artificial.
