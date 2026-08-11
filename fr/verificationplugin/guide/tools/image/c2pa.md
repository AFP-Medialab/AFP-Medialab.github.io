---
layout: page
title:  Provenance (C2PA)
lang: fr
urlPage: /tools/image/c2pa
---


## Informations générales

**C2PA (Coalition for Content Provenance and Authenticity)** est un standard ouvert permettant d'associer des métadonnées de provenance signées cryptographiquement aux fichiers multimédias. Cet outil lit les manifestes C2PA intégrés dans des images, vidéos et fichiers audio pour afficher la chaîne de custody — qui a créé ou modifié le contenu, quand et avec quels outils.

C2PA est pris en charge par un nombre croissant d'appareils photo, de téléphones et d'outils de création de contenu. Lorsqu'un fichier contient un manifeste C2PA valide, cet outil vérifie la signature cryptographique et affiche la chaîne de provenance.

## Comment l'utiliser

Vous pouvez l'utiliser en fournissant :
- une URL directe vers une image ou un fichier multimédia
- un fichier local via le bouton d'import de fichier

## Fonctionnement

L'outil lit le manifeste C2PA intégré, vérifie les signatures numériques auprès des certificats émetteurs, et affiche une vue structurée des données de provenance. Cela inclut le créateur, la date de création, l'historique des modifications et les assertions formulées sur le contenu.

## Cas d'usage

- Vérifier qu'une image a été capturée par un appareil photo ou un dispositif spécifique
- Vérifier si un contenu généré par IA a été étiqueté comme tel par l'outil générateur
- Consulter l'historique des modifications d'un fichier multimédia

## Notes importantes

- L'absence de manifeste C2PA ne **signifie pas** que le contenu est inauthentique. De nombreux fichiers légitimes n'incluent pas encore de données de provenance.
- Une signature valide confirme uniquement l'authenticité du manifeste lui-même, et non nécessairement la véracité de ses affirmations.
