---
layout: page
title:  FFMPEG Toolkit
lang: es
urlPage: /tools/other/ffmpegtoolkit
---


## Información general

**FFMPEG Toolkit** proporciona una interfaz basada en navegador para operaciones comunes de procesamiento de vídeo y audio con FFmpeg. Permite a los profesionales de la verificación realizar extracción de fotogramas, conversión de formatos, eliminación de audio y otras tareas de procesamiento multimedia sin necesidad de instalar FFmpeg localmente ni usar la línea de comandos.

## Cómo usarlo

Cargue un archivo de vídeo o audio local. Seleccione la operación que desea realizar entre las opciones disponibles. La herramienta procesa el archivo en el navegador y le permite descargar el resultado.

## Operaciones disponibles

- Extraer fotogramas individuales o secuencias de fotogramas de un vídeo
- Convertir entre formatos de vídeo y audio
- Eliminar el audio de un archivo de vídeo
- Recortar un vídeo a un intervalo de tiempo específico
- Extraer la pista de audio como archivo independiente

## Cómo funciona

La herramienta utiliza FFmpeg compilado en WebAssembly (WASM), que se ejecuta completamente en el navegador. No se sube ningún dato de vídeo a un servidor.

## Casos de uso

- Extraer fotogramas de un vídeo para su posterior análisis de imagen
- Preparar archivos multimedia para enviarlos a otras herramientas de verificación
- Convertir formatos propietarios a formatos estándar para su análisis
