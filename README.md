# Développement d'une Preuve de Concept

Ce dépôt se concentre sur le développement d'une preuve de concept (PoC) pour résoudre des problèmes spécifiques en science des données. Cela implique d'identifier des sources d'informations fiables, d'utiliser des méthodes de pointe, et de rester à jour avec les dernières tendances en science des données.

## Compétences Évaluées

- **Identifier des Sources d'Informations Fiables et Pertinentes** : Identifier des données et des sources d'informations fiables pouvant fournir des insights précieux pour les projets en science des données.

- **Identifier des Méthodes de Pointe pour Résoudre les Problèmes de Science des Données** : Explorer et sélectionner les méthodes avancées considérées comme les meilleures pratiques dans le domaine de la science des données.

- **Développer une Preuve de Concept pour les Problèmes de Science des Données** : Créer un prototype démontrant la faisabilité et la praticabilité de la solution proposée en science des données.

- **Effectuer une Recherche Continue sur les Tendances en Science des Données** : Se tenir au courant des derniers développements, techniques et outils en science des données pour améliorer continuellement la PoC.

## Plan du Projet

### Projet 7 : Développez une preuve de concept
**Objectif** : Améliorer les performances de MobileNetV3 en traitant les données déséquilibrées.

### Plan de Travail Prévisionnel
1. **Exploration du Jeu de Données**
   - Sélection du jeu de données (CWD30 - images et étiquettes de classification)
   - Chargement des données
   - Analyse exploratoire des données (E.D.A.)
   - Visualisation des données déséquilibrées

2. **Préparation des Données**
   - Prétraitement des données
   - Division des données en ensembles d'apprentissage, de validation et de test

3. **Modèle MobileNetV3Small - Baseline**
   - Chargement du modèle pré-entraîné MobileNetV3
   - Ajustement fin du modèle avec l'ensemble d'apprentissage
   - Recherche des hyperparamètres les plus performants pour ce modèle
   - Évaluation des performances sur l'ensemble de validation

4. **Pondération des Échantillons lors de l'Entraînement**
   - Gestion du déséquilibre des classes par pondération
   - Ajustement fin du modèle avec l'ensemble d'apprentissage

5. **Sous-échantillonnage des Classes Majoritaires**
   - Technique de rééquilibrage par sous-échantillonnage
   - Ajustement fin du modèle avec l'ensemble d'apprentissage

6. **Implémentation de DenseWeight & LMFLoss**
   - Définition du modèle avec DenseWeight pour la croissance des plantes et LMFLoss pour les espèces
   - Ajustement fin du modèle avec l'ensemble d'apprentissage
   - Recherche des hyperparamètres les plus performants pour ce modèle
   - Évaluation des performances sur l'ensemble de validation

7. **Comparaison des Performances**
   - Comparaison des performances entre les différents modèles
   - Analyse des résultats obtenus

8. **Conclusion**
   - Rédaction d'un rapport détaillé sur les résultats, les méthodes utilisées et les conclusions tirées
   - Documentation du code et des expériences réalisées pour faciliter la réutilisation et la compréhension du projet

## Sources Bibliographiques

- **CWD30** : [A Comprehensive and Holistic Dataset for Crop Weed Recognition in Precision Agriculture](https://arxiv.org/pdf/2305.10084.pdf)
- **MobileNets** : [Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/pdf/1704.04861.pdf)
- **Searching for MobileNetV3** : [Searching for MobileNetV3](https://arxiv.org/pdf/1905.02244.pdf)
- **LMFLOSS** : [A Hybrid Loss For Imbalanced Medical Image Classification](https://arxiv.org/pdf/2212.12741.pdf)
- **Focal Loss** : [Focal Loss for Dense Object Detection](https://arxiv.org/pdf/1708.02002.pdf)
- **Label-Distribution-Aware Margin Loss** : [Learning Imbalanced Datasets with Label-Distribution-Aware Margin Loss](https://arxiv.org/pdf/1906.07413.pdf)
- **Density-based Weighting for Imbalanced Regression** : [Density-based weighting for imbalanced regression](https://link.springer.com/article/10.1007/s10994-021-06023-5)
- **Revue des Algorithmes de Classification d'Images Basés sur les CNN** : [Review of Image Classification Algorithms Based on Convolutional Neural Networks](https://www.mdpi.com/2072-4292/13/22/4712)
- **Label-Imbalanced and Group-Sensitive Classification** : [Label-Imbalanced and Group-Sensitive Classification under Overparameterization](https://arxiv.org/abs/2103.01550)

