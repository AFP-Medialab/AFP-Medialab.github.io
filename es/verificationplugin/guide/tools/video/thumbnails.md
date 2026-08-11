---
layout: page
title:  Thumbnails
lang: es
urlPage: /tools/video/thumbnails
---


## Información general

**YouTube Thumbnails** es una alternativa de clasificación rápida que evita el procesamiento completo del vídeo. Recupera automáticamente las cuatro imágenes de vista previa generadas por defecto por el sistema para un vídeo de YouTube directamente a través de la API de YouTube, permitiendo a los analistas realizar búsquedas inversas de imágenes rápidas antes de comprometerse con análisis fotograma a fotograma más laboriosos.

## Cómo usarlo

Proporcione una URL de un vídeo de YouTube. La herramienta recuperará y mostrará las cuatro imágenes en miniatura predeterminadas asociadas al vídeo.

## Cómo funciona

La herramienta consulta la API de YouTube para recuperar las imágenes en miniatura estándar generadas por la plataforma en el momento de la carga. Cada miniatura puede usarse a continuación como punto de partida para búsquedas inversas de imágenes.

## Casos de uso

- Comprobar rápidamente si la imagen de vista previa de un vídeo ha sido utilizada en otros contextos
- Detectar contenido reciclado o reutilizado antes de realizar un análisis completo de fotogramas
- Identificar discrepancias entre una miniatura y el contenido real del vídeo

## Notas importantes

- Esta herramienta solo funciona con URLs de YouTube.
- Las miniaturas son generadas por YouTube y pueden no ser representativas de los momentos más significativos del vídeo. Utilice la [extracción de fotogramas clave](keyframes) para un análisis más completo a nivel de fotograma.