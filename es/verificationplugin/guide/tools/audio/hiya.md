---
layout: page
title:  Hiya
lang: es
urlPage: /tools/audio/hiya
---


## Información general

**Hiya** es una herramienta de análisis de audio para detectar voz sintética o generada por IA, integrada en la suite tras la adquisición por parte de Hiya de la startup especializada en IA de voz Loccus. A medida que las tecnologías de clonación de voz y síntesis de texto a voz se vuelven más accesibles, el audio sintético se utiliza cada vez más para fabricar declaraciones de figuras públicas o difundir desinformación mediante grabaciones de voz falsas.

## Cómo usarlo

Proporcione una URL de un archivo de audio o vídeo, o cargue un archivo local. La herramienta analizará la pista de audio y devolverá una puntuación de confianza que indica la probabilidad de que el habla haya sido generada por IA.

## Cómo funciona

En lugar de convertir el audio en texto, la herramienta pasa los datos de voz directamente a través de un Ensemble Listening Model para inspeccionar irregularidades en el tono, los patrones acústicos y las firmas de prosodia. La herramienta evalúa flujos de audio sin procesar para detectar ataques de voz sintética y clones de voz deepfake, proporcionando una puntuación de manipulación en aproximadamente cinco segundos.

## Casos de uso

- Verificar si una grabación de voz de una figura pública es auténtica
- Detectar contenido de voz generado por IA en vídeos o podcasts
- Apoyar investigaciones sobre campañas de medios sintéticos

## Notas importantes

- Los resultados deben tratarse como indicativos, no como concluyentes. El juicio editorial humano es siempre necesario.
- La precisión de la detección puede variar según la calidad del audio, la compresión y el modelo específico de síntesis de voz utilizado.
