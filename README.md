# README.md - Analyse des Capacités de Production d'Énergie d'EDF et Qualité du Vin

## Description du projet

Ce projet analyse deux jeux de données distincts : 
1. Les capacités de production d'énergie par pays pour le groupe EDF.
2. Les caractéristiques chimiques et qualités des vins rouges.

Le but est de fournir des insights sur les distributions des différentes sources d'énergie utilisées par EDF, ainsi que d'explorer les facteurs qui influencent la qualité des vins rouges.

## Structure du projet

Le code source, écrit en Python, utilise principalement les bibliothèques pandas, numpy, matplotlib, sklearn pour charger, manipuler, analyser et visualiser les données.

### Données

#### Capacités de production d'énergie
Extraction du fichier `capacites-de-production-par-pays-du-groupe-edf.csv`, contenant des informations sur les types d'énergie et leurs capacités de production par pays.

#### Qualité du vin
Analyse du fichier `winequality-red.csv`, qui contient des données sur les propriétés chimiques des vins rouges et leur qualité évaluée.

### Nettoyage des données

- Suppression des colonnes non pertinentes.
- Gestion des valeurs manquantes.
- Identification et suppression des valeurs aberrantes.

### Analyse exploratoire

- Visualisation des capacités de production par type d'énergie.
- Visualisation des relations entre les propriétés chimiques des vins et leur qualité.

## Visualisations

Les graphiques générés permettent de visualiser :

- La répartition des capacités de production par filière pour EDF.
- Les tendances des capacités de production sur plusieurs années.
- Corrélations entre les caractéristiques chimiques des vins et leur qualité.

## Analyses supplémentaires

- Utilisation de PCA, t-SNE, et LLE pour réduire les dimensions et mieux visualiser les données des vins.
- Modélisation prédictive pour estimer la qualité du vin basée sur ses caractéristiques chimiques.

## Usage

Pour exécuter ce projet, installez les dépendances suivantes :

```bash
pip install pandas numpy matplotlib sklearn
