# Titre du Notebook: Modélisation des Accidents de la Route

## Présentation du projet 
Ce projet vise à analyser et prédire la gravité des accidents de la route en France, en utilisant des données ouvertes fournies par le site data.gouv.fr, le portail français de l'open data. L'ensemble de données se compose de quatre fichiers CSV distincts, chacun apportant des informations cruciales sur les accidents de la route, les lieux où ils se sont produits, les véhicules impliqués, et les victimes concernées.


## But du projet 

A l'aide d'une API dans le dossier Shared du workspace de Databricks dans lequel il est possible de tester votre modèle avec des exemples d'accidents.

## Sommaire du repository

### Description des données
### Importation de tous les outils
### Importer des csv
####  Importer des csv dans le Filestore
####  Convertir un dataframe pandas en spark
####  Sauvegarder dans une table
####  Importer une table
####  Traitement des valeurs manquantes
####  Features selection et encodage des variables
#####    Encodage de hrmn, du mois et de la position GPS
#####    Encodage One-Hot des variables catégoriques (indispensable pour XGBoost et Random Forest)
### Train / Test
### Les models
####   Fit KNN model
####  Construire un modèle de DecisionTreeClassifier.
####  Construire un modèle de Random Forest.
####  Calculer les métriques (accuracy, f1-score) du meilleur modèle de chaque méthode pour comparer leur performance en vous aidant du tutoriel.
### Inscrire son modele avant deploiment

## le modèle retenu et ses performances

Random Forest - Exactitude: 0.64, Score F1: 0.62



 






