# Machine Learning - Clustering et réduction de dimension

## Présentation

Projet de Machine Learning réalisé sur un dataset de smartphones, dont l'objectif était d'étudier la structure des données et d'analyser leur capacité à former des groupes correspondant aux différentes catégories de `price_range`.

Le dataset contient **4 classes de prix** (`price_range` : 0, 1, 2 et 3). Les classes étant connues, elles ont été utilisées pour évaluer les résultats des méthodes de clustering.

## Objectifs

- Explorer et préparer le dataset
- Analyser les différentes variables
- Appliquer plusieurs méthodes de clustering
- Comparer les clusters obtenus aux classes réelles
- Évaluer la qualité des regroupements
- Réduire la dimension des données avec PCA
- Étudier les relations entre groupes de variables avec CCA
- Analyser l'impact de la réduction de dimension sur les résultats du clustering

## Méthodes utilisées

### Clustering

- K-Means
- Clustering hiérarchique
- Spectral Clustering

### Réduction de dimension

- PCA (Principal Component Analysis)
- CCA (Canonical Correlation Analysis)

### Évaluation

Les résultats des clusters ont été comparés aux classes réelles `price_range` à l'aide de :

- Rand Index
- Adjusted Rand Index
- Homogeneity
- Completeness
- V-measure
- Silhouette Score
- Matrices de contingence

## Résultats

Les différentes méthodes de clustering ont montré une correspondance limitée avec les véritables classes `price_range`.

Les scores obtenus étaient globalement faibles, indiquant que les méthodes de clustering étudiées ne permettaient pas de séparer efficacement les smartphones selon leur gamme de prix.

L'application de PCA et la réduction de dimension n'ont pas permis d'améliorer les performances du clustering. Les résultats obtenus après réduction étaient même globalement moins bons.

L'analyse a également permis de mettre en évidence l'importance relative des différentes variables dans la séparation des catégories de prix.

## Technologies

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Machine Learning
- Clustering
- PCA
- CCA
- Data Analysis

## Compétences développées

- Prétraitement et exploration de données
- Analyse statistique
- Machine Learning non supervisé
- Clustering
- Réduction de dimension
- Évaluation de modèles
- Visualisation de données
- Analyse et interprétation des résultats
