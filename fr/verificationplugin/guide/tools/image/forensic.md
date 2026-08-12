---
layout: page
title:  Forensic
lang: fr
urlPage: /tools/image/forensic
---


## Informations générales

L'analyse **forensique d'image** vise à détecter des anomalies et de possibles falsifications dans le signal de l'image. C'est un outil complexe qui implique une analyse mathématique du signal pour détecter des traces dans la compression de l'image, des incohérences dans les fréquences, la distribution des pixels et le bruit résiduel. Il peut également détecter les traces laissées par des falsifications issues du deep learning.
Ces traces ne sont pas uniquement causées par des falsifications. Elles peuvent également être déclenchées par le dématriçage (la façon dont les appareils photo interpolent les pixels pour construire des images numériques), la surexposition (trop de lumière dans certaines parties de l'image) ou par des textures d'objets complexes ou saturées telles que les zones noires ou blanches, les zones quadrillées.
Par conséquent, l'analyse forensique doit être utilisée avec prudence. Plus de filtres mettent en évidence une zone particulière, plus il est probable que l'image ait subi une manipulation.
Néanmoins, c'est un outil puissant pour révéler des falsifications, notamment si l'image originale ne peut pas être retrouvée par une recherche par similarité.

## Comment l'utiliser

Vous pouvez l'utiliser soit en fournissant :
 - un lien direct vers **une image** sur n'importe quelle page web (*de préférence un lien JPEG*) ;
 - en faisant un clic droit (*via le menu contextuel*) sur n'importe quelle image sur le web (*veuillez noter que les images encapsulées dans du code et non entièrement disponibles publiquement peuvent ne pas fonctionner*), ou
 - en utilisant le **bouton de fichier local** et en important via l'interface graphique sous-jacente une image locale depuis votre propre disque.

 Les résultats sont séparés en 4 catégories :
 - Compression
 - Traces
 - Apprentissage profond
 - Clonage

## Cas d'usage
- Analyser une image pour vérifier si certaines parties présentent une altération du signal

## Notes importantes
- L'altération du signal peut avoir plusieurs origines (modification manuelle, compression, etc.) ; les traces ne peuvent pas être considérées comme une preuve d'inauthenticité