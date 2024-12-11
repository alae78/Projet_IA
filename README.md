# **Classification Multi-Classes avec Machine Learning**

Ce projet met en œuvre plusieurs algorithmes de classification supervisée (régression logistique, SVM, KNN, et arbre de décision) pour résoudre un problème de classification multi-classes. À l'aide de techniques d'évaluation avancées et de visualisations, nous comparons les performances des modèles afin de déterminer le plus performant.

---

## **Contenu**

- [Aperçu du projet](#aperçu-du-projet)
- [Données](#données)
- [Modèles utilisés](#modèles-utilisés)
- [Évaluation des performances](#évaluation-des-performances)
- [Installation](#installation)
- [Résultats](#résultats)

---

## **Aperçu du projet**

L'objectif de ce projet est de construire et d'évaluer des modèles de classification capables de prédire avec précision des classes à partir de données simulées ou réelles. Nous comparons plusieurs algorithmes en utilisant des métriques comme l'accuracy, l'AUC, et des visualisations telles que la matrice de confusion et les courbes ROC.

---

## **Données**

- **Source des données** : Données simulées générées avec Scikit-learn pour représenter un problème multi-classes.
- **Caractéristiques principales** :
  - Nombre d'instances : 5001
  - Nombre de classes : 4
  - Nombre de caractéristiques : 10

---

## **Modèles utilisés**

1. **Régression logistique** : 
   - Méthode simple et efficace pour les problèmes linéaires.
2. **SVM (Support Vector Machine)** :
   - Utilisation de noyaux linéaires et non linéaires.
3. **K-Nearest Neighbors (KNN)** :
   - Algorithme basé sur la proximité des données.
4. **Arbre de décision** :
   - Approche simple et interprétable.

---

## **Évaluation des performances**

Les performances des modèles ont été évaluées à l'aide de :
- **Courbes ROC et AUC** pour mesurer la capacité de classification.
- **Matrices de confusion** pour analyser les erreurs de prédiction.
- **Rapport de classification** (précision, rappel, F1-score) pour chaque classe.

