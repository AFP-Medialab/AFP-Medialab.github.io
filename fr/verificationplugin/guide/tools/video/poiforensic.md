---
layout: page
title:  POI Forensics
lang: fr
urlPage: /tools/video/poiforensic
---


## Informations générales

**POI (Person of Interest) Forensics** est un outil permettant d'identifier et d'analyser des individus spécifiques dans des contenus vidéo et image. Il permet aux enquêteurs de vérifier que la vidéo d'une personne d'intérêt sélectionnée au préalable est authentique.

## Comment l'utiliser

Vous pouvez analyser une vidéo en :
- fournissant une URL directe vers une vidéo (YouTube, Twitter/X, Facebook, Telegram et autres sont pris en charge)
- important un fichier vidéo local

Vous pouvez choisir la personne d'intérêt présente dans la vidéo importée (les personnes d'intérêt disponibles sont : Macron, Meloni, Poutine, Trump et Zelensky). Vous devez également choisir un « mode », selon que vous pensez que l'audio ou la vidéo est faux.

L'outil renvoie ensuite un score de confiance indiquant la probabilité que la vidéo soit inauthentique, et fournit un graphique temporel de toutes les détections de visages avec leurs scores associés.

## Fonctionnement

L'outil dispose en mémoire d'un modèle biométrique pour chaque personne d'intérêt disponible. Il pré-traite la vidéo en extrayant chaque visage, puis compare chaque visage au modèle biométrique. Lorsque le score est faible (inférieur à 1), le visage est suffisamment proche du modèle biométrique réel pour être considéré comme la vraie personne. Lorsqu'il est supérieur, le visage est trop différent : c'est soit un faux, soit simplement une autre personne que la personne d'intérêt.

## Cas d'usage

- Soutenir les investigations de fact-checking impliquant des personnalités publiques

## Notes importantes

- Les résultats doivent toujours être examinés par un analyste humain.
- La reconnaissance faciale comporte une incertitude inhérente — ne traitez pas les correspondances comme des identifications définitives.
- Les résultats peuvent sembler inhabituels lorsque d'autres personnes apparaissent dans la vidéo et sont comparées à la personne d'intérêt. Dans ce cas, analysez uniquement la piste associée à la personne d'intérêt.
