---
layout: page
title:  Social Network Analysis
lang: fr
urlPage: /tools/data/sna
---


## Informations générales

**Social Network Analysis (SNA)** fournit des outils pour capturer, analyser et visualiser des données de réseaux sociaux en temps réel. Il vous permet d'enregistrer l'activité autour d'un sujet, d'un hashtag ou d'un compte, et d'analyser le réseau d'interactions résultant pour identifier les acteurs clés, les flux d'information et les comportements coordonnés.

## Comment l'utiliser

Utilisez les contrôles d'enregistrement pour capturer des données depuis une source de réseau social (configurez la cible dans le menu des paramètres ou via l'outil X Search). Une fois les données collectées, ouvrez l'outil SNA pour visualiser le réseau.

Vous pouvez également importer des données préalablement collectées pour les analyser.

## Fonctionnement

L'outil construit un graphe où les nœuds représentent des comptes et les arêtes représentent des interactions (retweets, réponses, mentions). Des métriques réseau telles que la centralité, le regroupement et la détection de communautés sont calculées pour mettre en évidence les acteurs influents et les schémas structurels. Des sous-utilitaires avancés incluant CoorTweet et D3LTA sont utilisés pour analyser les réseaux sémantiques, cartographier les tendances d'amplification et découvrir les comportements inauthentiques coordonnés (CIB) à travers les flux des plateformes.

## Cas d'usage

- Identifier les comptes clés qui portent un narratif ou un hashtag
- Détecter des groupes de comptes qui coordonnent l'amplification de contenus
- Cartographier la structure d'une opération d'information
- Analyser la propagation d'un contenu à travers un réseau dans le temps

## Outils associés

- [Twitter SNA](twittersna) — SNA spécifique à Twitter avec capture directe via API
- [CSV SNA](csvsna) — SNA à partir de jeux de données CSV exportés
