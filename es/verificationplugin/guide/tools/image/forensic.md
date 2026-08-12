---
layout: page
title:  Forensic
lang: es
urlPage: /tools/image/forensic
---


## Información general

El análisis **forense de imágenes** tiene como objetivo detectar anomalías y posibles falsificaciones en la señal de la imagen. Es una herramienta compleja que implica un análisis matemático de la señal para detectar trazas en la compresión de la imagen, incoherencias en frecuencias, en la distribución de píxeles y en el ruido residual. También puede detectar las huellas dejadas por falsificaciones de deep learning.
Estas trazas no solo son causadas por falsificaciones. También pueden ser provocadas por el demosaicizado (la forma en que las cámaras interpolan píxeles para construir imágenes digitales), por la sobreexposición (demasiada luz en algunas partes de la imagen) o por texturas complejas o saturadas de objetos, como zonas negras o blancas y áreas reticuladas.
Por tanto, el análisis forense debe utilizarse con cautela. Cuantos más filtros destaquen una zona concreta, más probable es que la imagen haya sido manipulada.
No obstante, es una herramienta poderosa para revelar falsificaciones, especialmente si la imagen original no puede recuperarse mediante búsqueda por similitud.

## Cómo usarlo

Puede utilizarlo proporcionando:
- un enlace directo a **una imagen** en cualquier página web (*preferiblemente un enlace JPEG*);
- haciendo clic derecho (*usando el menú contextual*) en cualquier imagen de la web (*tenga en cuenta que las imágenes encapsuladas en código y no disponibles públicamente pueden no funcionar*); o
- usando el **botón de archivo local** y cargando en la interfaz gráfica subyacente una imagen local desde su propio disco.

Los resultados se dividen en 4 categorías:
- Compresión
- Trazas
- Aprendizaje profundo
- Clonado

## Casos de uso

- Analizar una imagen para ver si alguna parte presenta alguna alteración de señal

## Notas importantes

- La alteración de la señal puede tener múltiples orígenes (edición manual, compresión, etc.); las trazas no pueden considerarse como prueba de inautenticidad.