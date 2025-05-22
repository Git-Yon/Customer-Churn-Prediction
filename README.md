# Plan du projet Prédiction du Churn Client

## 1. Problématique business
- Ciblage marketing et fidélisation
- Importance économique de la fidélisation
- Description du dataset (clients d’un opérateur télécom)

- Objectif principal : prédire le churn
- Objectifs secondaires : comprendre les facteurs, créer un modèle réutilisable

## 2. Chargement des données
- Importation des librairies
- Aperçu et nettoyage des données
  
## 3. Nettoyage et préparation des données
- Valeurs manquantes 

## 4. Analyse exploratoire
- Vue d’ensemble
- Comportement de churn
- KPIs business

## 5. Modélisation prédictive
- Split des données
- Target Encoding / Standardisation
-  XGBOOST / GridSearch
-  Visualisation des résultats

## 6. Interprétation du modèle avec SHAP
- Importance des variables
- Analyse visuelle des effets (contrat, mensualités…)

## 7. Recommandations métier
- Actions prioritaires par segment
- Stratégies de rétention basées sur les insights SHAP
- Estimation du ROI potentiel

## Améliorations possibles
- Validation croisée à ajouter
- Gestion du déséquilibre (SMOTE, poids de classe)
- Sérialisation du modèle (joblib/pickle)
- Choix explicite du seuil de décision
