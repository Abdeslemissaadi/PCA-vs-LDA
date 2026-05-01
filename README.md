# Étude Comparative : PCA vs LDA

## Description du Projet
Ce projet explore et compare deux méthodes fondamentales de réduction de dimensionnalité : l'**Analyse en Composantes Principales (PCA)** et l'**Analyse Discriminante Linéaire (LDA)**. 
À travers l'utilisation du dataset *Iris*, ce travail illustre comment le choix entre une approche non-supervisée (PCA) et supervisée (LDA) influence la capacité de séparation des classes et, in fine, la précision d'un modèle de classification.

## Objectifs de l'Étude
- Visualiser la structure des données en 2D.
- Comprendre la différence entre maximisation de la variance (PCA) et maximisation de la séparabilité des classes (LDA).
- Évaluer la robustesse des modèles via validation croisée.
- Interpréter visuellement les frontières de décision.

## Méthodologie
1. **Prétraitement** : Normalisation des données (`StandardScaler`) pour assurer une mise à l'échelle équitable.
2. **Réduction** : Application de PCA pour la conservation de la variance et de LDA pour l'optimisation de la séparation.
3. **Validation** : Mise en œuvre d'une validation croisée (5-folds) pour mesurer la fiabilité du classifieur.
4. **Visualisation** : Tracé des frontières de décision pour observer comment chaque technique segmente l'espace des caractéristiques.

## Technologies Utilisées
- **Langage** : Python
- **Bibliothèques** : `scikit-learn` (PCA, LDA, Pipeline, Metrics), `matplotlib` (Visualisation), `numpy/pandas` (Manipulation de données).

## Principaux Apprentissages
- **PCA** est idéal pour l'exploration de données et la réduction de bruit sans connaissance des labels.
- **LDA** excelle dans les tâches de classification en forçant la séparation entre les classes.
- L'utilisation de `Pipelines` et de la `Validation Croisée` garantit une approche reproductible et exempte de biais (overfitting).

---
*Ce projet est une excellente démonstration de la compréhension des mécanismes sous-jacents aux algorithmes de Machine Learning.*
