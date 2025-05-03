# Budget Analyst : Analyse des Écarts Budgétaires

## Contexte

Ce projet a été réalisé dans le cadre d'un portfolio d'étudiante en Master 1 Data Analyst en reconversion professionnelle. Il vise à illustrer de manière concrète les compétences essentielles d'une analyste de données, notamment :

* La création et la manipulation de jeux de données
* L'analyse d'écarts budgétaires
* L'utilisation de Python, SQL et Power BI
* La structuration d'un projet réaliste, clair et facilement compréhensible

## Objectif du projet

Comparer un budget prévisionnel à des dépenses réelles afin d'identifier les écarts, les visualiser et en tirer des enseignements pour améliorer les prévisions futures.

## Structure du projet

Le projet est organisé en plusieurs fichiers et dossiers permettant de suivre une progression logique et pédagogique :

## Prérequis

Avant de commencer, assurez-vous d'avoir :

* Python 3.8 ou plus
* pip installé
* sqlite3 installé (généralement présent par défaut)

## Installation et exécution rapide

Cloner le projet, installer les dépendances et tout exécuter d'un coup :

```bash
git clone https://github.com/ondouavivi/budget_analyst.git
cd budget_analyst
pip install -r requirements.txt
python run_all.py
```

Ce script va :

1. Générer deux jeux de données (budget et réel)
2. Calculer les écarts et générer des graphiques
3. Stocker les données dans une base SQLite locale

Vous obtiendrez :

* `merged_budget.csv`
* `budget.db avec toutes les données insérées`
* Deux graphiques au format `.png`

## Requêtes SQL

Pour analyser les écarts avec SQL :

```bash
sqlite3 budget.db < sql_queries.sql
```
## Graphique image png

Cela affichera :

* Les écarts totaux par catégorie
* Le mois avec l'écart le plus important
* Les catégories les plus régulièrement dépassées