---
layout: page
title:  Deepfake Video Detection
lang: fr
urlPage: /tools/video/deepfake
---


## Informations générales

**Deepfake video detection** est un environnement forensique expérimental développé par ITI CERTH qui analyse des vidéos pour identifier les visages générés ou manipulés par IA. Les deepfakes utilisent des modèles d'apprentissage profond (généralement des GAN ou des méthodes basées sur la diffusion) pour synthétiser ou échanger des visages dans des vidéos, produisant souvent des résultats difficiles à détecter à l'œil nu.

Cet outil surveille les séquences vidéo via un ensemble de modèles de réseaux de neurones convolutifs (CNN), dont Xception et EfficientNet-B4, entraînés à reconnaître les artefacts introduits par le processus de synthèse, tels que les incohérences dans la fusion des visages, les schémas de clignement non naturels et les anomalies dans le domaine fréquentiel.

## Comment l'utiliser

Vous pouvez analyser une vidéo en :
- fournissant une URL directe vers une vidéo (YouTube, Twitter/X, Facebook, Telegram et autres sont pris en charge)
- important un fichier vidéo local

L'outil retourne un score de confiance indiquant la probabilité que les visages présents dans la vidéo aient été générés ou substitués de manière synthétique.

## Fonctionnement

Le système cartographie les trajectoires faciales sur des sous-segments de la vidéo, extrait les régions faciales des images et les fait passer par l'ensemble de détection. Il détecte l'échange de visages et la réanimation faciale en renvoyant une chronologie de probabilité localisée tracée sur des segments discrets du fichier vidéo, plutôt qu'un score unique pour l'ensemble de la vidéo.

## Notes importantes

- Un score de confiance élevé ne **constitue pas** une preuve de manipulation. Combinez toujours avec d'autres méthodes de vérification.
- L'outil est le plus efficace sur des images faciales en gros plan et bien éclairées.
- Une compression importante ou une faible résolution peut réduire la précision de la détection.
