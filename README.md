# Data Challenge – Modélisation des exacerbations de l’asthme

## Présentation du projet

Ce projet académique a été réalisé dans le cadre de mon Master en Intelligence des données de santé.

L’objectif de ce Data Challenge était d’explorer différentes approches de **Data Science et de Machine Learning appliquées à des données de santé**, autour de la problématique des exacerbations de l’asthme.

Le projet est organisé en trois parties complémentaires : **classification, régression et génération de données synthétiques**.

> Ce projet a été réalisé en travail de groupe, avec des équipes différentes pour les différentes parties du challenge.

---

## Partie 1 – Classification des exacerbations

La première partie porte sur un problème de **classification** visant à prédire la présence ou l’absence d’une exacerbation de l’asthme à partir des données disponibles.

### Objectifs

- Explorer et préparer les données
- Développer un modèle de classification
- Évaluer les performances prédictives
- Générer des prédictions sur de nouvelles observations

### Notebook

`partie1_classification_asthme.ipynb`

---

## Partie 2 – Régression du nombre d’exacerbations

La deuxième partie porte sur la **modélisation du nombre d’exacerbations**.

L’objectif est d’étudier une problématique de régression et d’explorer les relations entre les différentes variables et le nombre d’exacerbations observées.

### Objectifs

- Explorer les variables disponibles
- Préparer les données pour la modélisation
- Modéliser le nombre d’exacerbations
- Évaluer les performances du modèle
- Générer des prédictions

### Notebook

`partie2_regression_exacerbations.ipynb`

---

## Partie 3 – Génération de données synthétiques

La troisième partie explore la **génération de données synthétiques** à partir des données disponibles.

Cette approche permet d’aborder une problématique particulièrement importante dans le domaine de la santé : la création de données artificielles conservant certaines caractéristiques statistiques des données originales.

### Objectifs

- Explorer la structure des données
- Étudier leur représentation
- Générer de nouvelles observations synthétiques
- Comparer les données générées aux données initiales

### Notebook

`partie3_donnees_synthetiques.ipynb`

---

## Compétences mobilisées

- Python
- Jupyter Notebook
- Data Science
- Machine Learning
- Classification
- Régression
- Analyse exploratoire des données
- Préparation et transformation des données
- Évaluation de modèles
- Génération de données synthétiques
- Visualisation de données

---

## Structure du repository

```text
asthma-data-challenge/
│
├── README.md
├── partie1_classification_asthme.ipynb
├── partie2_regression_exacerbations.ipynb
├── partie3_donnees_synthetiques.ipynb
├── donnees_synthetiques.csv
└── .gitignore
