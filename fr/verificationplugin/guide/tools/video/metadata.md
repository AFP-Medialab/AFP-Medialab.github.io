---
layout: page
title:  Video Metadata
lang: fr
urlPage: /tools/video/metadata
---


## Informations générales

L'extraction de **métadonnées vidéo** récupère les informations techniques et descriptives intégrées dans un fichier vidéo. Cela inclut la date et l'heure de création, les coordonnées GPS (si disponibles), les informations sur l'appareil, les détails du codec, la durée, la résolution, la fréquence d'images et les paramètres d'encodage.

Les métadonnées peuvent révéler des informations importantes sur une vidéo : où et quand elle a été enregistrée, quel appareil a été utilisé, et si le fichier a été ré-encodé ou modifié depuis sa création originale.

## Comment l'utiliser

Vous pouvez l'utiliser en fournissant :
- une URL directe vers une vidéo sur une page web
- un fichier vidéo local via le bouton d'import de fichier

L'outil affichera tous les champs de métadonnées disponibles extraits du fichier vidéo ou de sa source en ligne.

## Fonctionnement

L'outil lit les en-têtes de métadonnées intégrées du fichier vidéo et, pour les vidéos en ligne, interroge également les métadonnées de la plateforme disponibles. Il affiche les propriétés techniques brutes ainsi que toute information géographique ou relative à l'appareil trouvée.

## Cas d'usage

- Vérifier l'origine ou la date revendiquée d'une vidéo
- Vérifier si une vidéo a été ré-encodée (ce qui peut indiquer une manipulation)
- Extraire des coordonnées GPS pour les recouper avec le lieu revendiqué
- Vérifier la résolution de la vidéo pour s'assurer qu'elle est standard (des dimensions inhabituelles prouvent qu'une modification a été apportée à la vidéo originale)
