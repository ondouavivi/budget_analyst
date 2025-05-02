# Budget Analyst : Analyse des Écarts Budgétaires

## Contexte

Ce projet a été réalisé dans le cadre d'un portfolio d'étudiante en Master 1 Data Analyst en reconversion professionnelle. Il vise à illustrer de manière concrète les compétences essentielles d'une analyste de données, notamment :

La création et la manipulation de jeux de données

L'analyse d'écarts budgétaires

L'utilisation de Python, SQL et Power BI

La structuration d'un projet réaliste, clair et facilement compréhensible

## Objectif du projet
Comparer un budget prévisionnel à des dépenses réelles afin d'identifier les écarts, les visualiser et en tirer des enseignements pour améliorer les prévisions futures.

## Structure du projet
Le projet est organisé en plusieurs fichiers et dossiers permettant de suivre une progression logique et pédagogique :

## Prérequis
Avant de commencer, assurez-vous d'avoir :

Python 3.8 ou plus

pip installé

sqlite3 installé (généralement présent par défaut)

Power BI Desktop (si vous souhaitez explorer le tableau de bord)

## Installation et exécution rapide
Cloner le projet, installer les dépendances et tout exécuter d'un coup :

git clone https://github.com/votre-utilisateur/budget-ecarts-analyse.git
cd budget-ecarts-analyse
pip install -r requirements.txt
python run_all.py

Ce script va :

Générer deux jeux de données (budget et réel)

Calculer les écarts et générer des graphiques

Stocker les données dans une base SQLite locale

Vous obtiendrez :

merged_budget.csv

budget.db avec toutes les données insérées

Deux graphiques au format .png

Requêtes SQL
Pour analyser les écarts avec SQL :

sqlite3 budget.db < sql_queries.sql
Cela affichera :

Les écarts totaux par catégorie

Le mois avec l'écart le plus important

Les catégories les plus régulièrement dépassées

Visualisation avancée avec Power BI
Ouvrez le fichier powerbi/dashboard.pbix dans Power BI Desktop. Le tableau de bord permet de :

Filtrer par catégorie ou mois

Visualiser les écarts dans le temps

Identifier les postes les plus déviants visuellement

Pourquoi cette structure ?
Cette organisation vise à :

Guider pas à pas une personne en apprentissage

Séparer clairement les différentes compétences : Python, SQL, BI

Favoriser les bonnes pratiques Git (commits progressifs, dossiers clairs)

Faciliter la lecture, l’évolution et la maintenance du projet

Licence
Projet éducatif open-source à usage d'apprentissage personnel.