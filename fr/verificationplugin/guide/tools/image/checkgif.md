---
layout: page
title:  CheckGIF
lang: fr
urlPage: /tools/image/checkgif
---


## Informations générales

**CheckGIF** prend deux images similaires en entrée et les superpose sur une même base pour créer un GIF annoté facilitant la détection des différences entre les deux. Il fonctionne sur des images légèrement modifiées grâce à une comparaison homographique permettant de superposer les images.

## Comment l'utiliser

Vous pouvez l'utiliser en fournissant :
- deux URL directes vers les images
- deux fichiers image locaux via le bouton d'import de fichier

L'outil superpose ensuite les images, et vous pouvez ajouter des annotations pour l'image supposément fausse ainsi que pour l'original. Vous pouvez modifier le contenu et le style des annotations (par exemple si vous avez besoin d'une langue non disponible dans le plugin). Vous pouvez ensuite les télécharger en GIF ou en MP4.

## Fonctionnement

L'outil compare les deux images et tente de les superposer par comparaison homographique. Il renvoie une erreur si les images ne sont pas suffisamment similaires.

## Cas d'usage

- Élément de communication pour montrer rapidement l'image falsifiée et l'original
- Pour les images falsifiées dont l'altération n'est pas visible à l'œil nu, la modification est mise en évidence par le format GIF