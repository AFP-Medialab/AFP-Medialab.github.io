---
layout: page
title:  POI Forensics
lang: es
urlPage: /tools/video/poiforensic
---


## Información general

**POI (Person of Interest) Forensics** es una herramienta para identificar y analizar personas específicas en contenido de vídeo e imagen. Permite a los investigadores verificar que el vídeo de una persona de interés seleccionada previamente es auténtico.

## Cómo usarlo

Puede analizar un vídeo:
- proporcionando una URL directa a un vídeo (se admiten YouTube, Twitter/X, Facebook, Telegram y otras plataformas)
- cargando un archivo de vídeo local

Puede elegir el POI que aparece en el vídeo cargado (los POI disponibles son: Macron, Meloni, Putin, Trump y Zelenskyy). También debe elegir un "modo", dependiendo de si cree que el audio es falso o el vídeo es falso.

La herramienta devuelve una puntuación de confianza que indica la probabilidad de que el vídeo sea inauténtico y proporciona un gráfico temporal de todas las detecciones faciales con sus puntuaciones asociadas.

## Cómo funciona

La herramienta tiene en memoria un modelo biométrico para cada POI disponible. Preprocesa el vídeo extrayendo todos los rostros y luego compara cada rostro con el modelo biométrico. Cuando la puntuación es baja (por debajo de 1), significa que el rostro se parece lo suficiente al modelo biométrico real como para considerar que es la persona real. Cuando está por encima, el rostro es demasiado diferente: es una falsificación o simplemente otra persona distinta al POI.

## Casos de uso

- Apoyar investigaciones de verificación de datos que involucren figuras públicas

## Notas importantes

- Los resultados siempre deben ser revisados por un analista humano.
- El reconocimiento facial tiene una incertidumbre inherente: no trate las coincidencias como identificaciones definitivas.
- Los resultados pueden parecer inusuales cuando hay otras personas en el vídeo que son detectadas y comparadas con el POI. En ese caso, analice únicamente la pista asociada al POI.
