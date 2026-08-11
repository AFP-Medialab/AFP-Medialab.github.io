---
layout: page
title:  Synthetic Image Detection
lang: fr
urlPage: /tools/image/syntheticimagedetection
---


## Fonctionnement

L'outil applique un ensemble de fusion multi-modèles combinant 14 réseaux de neurones distincts accélérés par GPU pour inspecter les irrégularités de motifs visuels, les artefacts dans le domaine fréquentiel, ainsi que les empreintes de génération GAN ou par diffusion latente. Il émet un verdict structuré en quatre niveaux de couleur :

- **Rouge** : Généré par IA
- **Orange** : Incertain
- **Vert** : Non détecté
- **Bleu** : En cours de révision humaine

Les résultats sont accompagnés d'un rapport de transparence mettant en évidence les anomalies de fusion des caractéristiques et les incohérences dans la structure architecturale de l'image.
