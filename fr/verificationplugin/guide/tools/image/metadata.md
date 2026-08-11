---
layout: page
title:  Metadata
lang: fr
urlPage: /tools/image/metadata
---


## Informations générales

**Metadata Viewer** examine les profils de métadonnées structurelles des fichiers image, en exposant les blocs EXIF, IPTC et XMP intégrés. Il extrait les signatures matérielles des appareils photo, les journaux des logiciels de retouche, les configurations d'objectifs et les coordonnées GPS pour vérifier la provenance historique d'une image.

## Comment l'utiliser

Vous pouvez l'utiliser en fournissant :
- une URL directe vers une image sur une page web
- un fichier image local via le bouton d'import de fichier
- en faisant un clic droit sur n'importe quelle image dans le navigateur

## Fonctionnement

L'outil analyse les blocs de métadonnées binaires intégrés dans le fichier image et présente les champs extraits dans un format structuré et lisible. Les coordonnées GPS peuvent être ouvertes directement dans une application cartographique pour vérification de localisation.

## Principaux champs de métadonnées

- **EXIF** : marque et modèle de l'appareil photo, données d'objectif, paramètres de prise de vue (vitesse d'obturation, ouverture, ISO), date et heure originales
- **IPTC** : auteur, droits d'auteur, légende, mots-clés ajoutés par les éditeurs
- **XMP** : historique de retouche, logiciels utilisés, balises de flux de travail
- **GPS** : latitude, longitude et altitude si enregistrées par l'appareil

## Cas d'usage

- Vérifier la date de prise de vue originale d'une photographie
- Identifier l'appareil photo ou le dispositif utilisé pour prendre une image
- Détecter des signes de post-traitement (logiciel de retouche, horodatages de modification)
- Extraire des coordonnées GPS pour corroborer ou réfuter une localisation revendiquée

## Notes importantes

- Les métadonnées peuvent être supprimées, modifiées ou falsifiées. L'absence de métadonnées ne confirme pas une manipulation, et leur présence ne garantit pas l'authenticité.
- De nombreuses plateformes de réseaux sociaux suppriment les données EXIF des images téléchargées. L'absence d'un champ GPS peut simplement refléter le comportement de la plateforme, et non une dissimulation intentionnelle.