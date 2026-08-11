---
layout: page
title:  Synthetic Image Detection
lang: es
urlPage: /tools/image/syntheticimagedetection
---


## Información general

**Synthetic Image Detection** identifica si una imagen ha sido generada por inteligencia artificial (p. ej., GANs, modelos de difusión como Stable Diffusion, Midjourney o DALL·E). Las imágenes generadas por IA son cada vez más realistas y se utilizan para difundir desinformación mediante la fabricación de fotografías de eventos, personas o lugares que no existen.

## Cómo usarlo

Puede usarlo proporcionando:
- una URL directa a una imagen en cualquier página web
- un archivo de imagen local mediante el botón de carga de archivos
- haciendo clic derecho sobre cualquier imagen en el navegador

## Cómo funciona

La herramienta aplica un ensemble de fusión multimodelo que combina 14 redes neuronales independientes aceleradas por GPU para inspeccionar irregularidades en patrones visuales, artefactos en el dominio de frecuencias y huellas de generación mediante GAN o difusión latente. Emite un veredicto estructurado de cuatro niveles de color:

- **Rojo**: Generado por IA
- **Naranja**: Incierto
- **Verde**: No detectado
- **Azul**: En revisión humana

Los resultados van acompañados de un informe de transparencia que destaca las anomalías de características fundidas e inconsistencias en la distribución arquitectónica.

## Notas importantes

- La precisión de la detección varía según el modelo de generación utilizado y cualquier postprocesamiento aplicado.
- Un resultado negativo (imagen clasificada como real) **no** garantiza que la imagen sea auténtica.
- Combine siempre los resultados con la búsqueda inversa de imágenes y el análisis de metadatos para una evaluación completa.
