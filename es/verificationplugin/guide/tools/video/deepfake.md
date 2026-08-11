---
layout: page
title:  Deepfake Video Detection
lang: es
urlPage: /tools/video/deepfake
---


## Información general

**Deepfake video detection** es un entorno forense experimental desarrollado por ITI CERTH que analiza vídeos para identificar rostros manipulados mediante inteligencia artificial. Los deepfakes utilizan modelos de aprendizaje profundo (típicamente GANs o métodos basados en difusión) para sintetizar o intercambiar rostros en vídeos, produciendo a menudo resultados difíciles de detectar a simple vista.

Esta herramienta monitoriza secuencias de vídeo mediante un ensemble de modelos de redes neuronales convolucionales (CNN), entrenados para reconocer artefactos introducidos por el proceso de síntesis, como inconsistencias en la fusión facial, patrones de parpadeo antinaturales y anomalías en el dominio de frecuencias.

## Cómo usarlo

Puede analizar un vídeo:
- proporcionando una URL directa a un vídeo (se admiten YouTube, Twitter/X, Facebook, Telegram y otras plataformas)
- cargando un archivo de vídeo local

La herramienta devuelve una puntuación de confianza que indica la probabilidad de que los rostros en el vídeo hayan sido generados o intercambiados sintéticamente.

## Cómo funciona

El sistema mapea las pistas faciales a lo largo de sub-segmentos del vídeo, extrayendo regiones faciales de los fotogramas y pasándolas por el ensemble de detección. Detecta el intercambio de rostros y la reanimación facial devolviendo una línea de tiempo de probabilidad localizada trazada a lo largo de fragmentos discretos del archivo de vídeo, en lugar de una puntuación única para todo el vídeo.

## Notas importantes

- Esta herramienta solo funciona con modificaciones faciales realizadas por IA; no funciona con vídeos generados íntegramente por IA.
- Una puntuación de confianza alta **no** constituye prueba de manipulación. Combine siempre los resultados con otros métodos de verificación.
- La herramienta es más eficaz con imágenes faciales de primer plano y bien iluminadas.
- Una compresión elevada o una resolución baja pueden reducir la precisión de la detección.
