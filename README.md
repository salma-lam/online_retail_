# Segmentation des Clients pour Optimisation des Stratégies Marketing

Ce mini-projet utilise des techniques d'apprentissage non supervisé pour analyser et segmenter les clients en fonction de leurs comportements d’achat. En utilisant le dataset "Online Retail", l’objectif est d'identifier des segments pertinents pour améliorer les stratégies marketing et offrir des recommandations personnalisées.

## Objectif du Projet
Le projet vise à regrouper les clients en segments en fonction de leur comportement d'achat. Cela permet de mieux comprendre les besoins des clients, de personnaliser les offres, et d'optimiser les stratégies marketing.

## Tâches à Réaliser

### 1. Analyse Descriptive du Dataset
   - **Explorer la distribution** : Quantités, prix unitaires, et valeurs totales par commande.
   - **Identifier les anomalies** : Factures annulées (quantité négative), clients sans identifiants, commandes inhabituelles.
   - **Calculer des indicateurs-clés** :
     - **Recency** : Dernière date d’achat par client.
     - **Frequency** : Nombre total de commandes par client.
     - **Monetary** : Valeur totale des achats par client.
   - **Visualiser les données** : Histogrammes, courbes de distribution, et boîtes à moustache (boxplots) pour repérer les valeurs extrêmes.

### 2. Prétraitement des Données
   - **Traiter les valeurs manquantes** et corriger ou exclure les données anormales (ex. quantité négative).
   - **Créer des variables dérivées**, comme le total dépensé par commande.
   - **Standardiser les variables** pour faciliter l'entraînement des modèles de clustering.

### 3. Segmentation des Clients
   - **Appliquer K-means** pour regrouper les clients en plusieurs segments.
   - **Tester d'autres méthodes** : DBSCAN, analyse RFM (Récence, Fréquence, Monétaire).

### 4. Optimisation des Hyperparamètres
   - Utiliser **la méthode du coude** ou **le silhouette score** pour déterminer le nombre optimal de clusters.
   - Ajuster les paramètres de clustering pour maximiser la cohérence et la pertinence des segments.

### 5. Visualisation et Interprétation des Résultats
   - **Visualiser les segments** avec des boîtes à moustache pour chaque segment, montrant la distribution des dépenses et des fréquences d’achat.
   - **Comparer les clusters** avec des diagrammes en nuage de points et des graphiques à barres.
   - Analyser les valeurs atypiques détectées à l’intérieur des clusters.

## Prérequis

- Python 3.x
- Bibliothèques : `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

