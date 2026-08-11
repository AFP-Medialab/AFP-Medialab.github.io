---
layout: page
title:  Video Metadata
lang: es
urlPage: /tools/video/metadata
---


## Información general

La extracción de **metadatos de vídeo** recupera la información técnica y descriptiva incrustada en un archivo de vídeo. Esto incluye fecha y hora de creación, coordenadas GPS (cuando están disponibles), información del dispositivo, detalles del códec, duración, resolución, velocidad de fotogramas y parámetros de codificación.

Los metadatos pueden revelar contexto importante sobre un vídeo: dónde y cuándo se grabó, qué dispositivo se utilizó y si el archivo ha sido recodificado o editado desde su creación original.

## Cómo usarlo

Puede utilizarlo proporcionando:
- una URL directa a un vídeo en una página web
- un archivo de vídeo local mediante el botón de carga de archivos

La herramienta mostrará todos los campos de metadatos disponibles extraídos del archivo de vídeo o de su fuente en línea.

## Cómo funciona

La herramienta lee las cabeceras de metadatos incrustadas en el archivo de vídeo y, para vídeos en línea, también consulta los metadatos de la plataforma disponibles. Muestra las propiedades técnicas sin procesar junto con cualquier información geográfica o del dispositivo encontrada.

## Casos de uso

- Verificar el origen o la fecha reclamados de un vídeo
- Comprobar si un vídeo ha sido recodificado (lo que puede indicar manipulación)
- Extraer coordenadas GPS para contrastar con la ubicación reclamada
- Comprobar la resolución del vídeo para verificar que el ancho y la altura son habituales (un número inusual demuestra que se ha realizado una edición en el vídeo original)
