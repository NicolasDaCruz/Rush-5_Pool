# Rush5 Project

## Dashboard Looker 
Un dashbord looker studio à été créé pour avoir une meilleure vision des données
https://lookerstudio.google.com/s/teCsp76ilU0

## Description

Ce projet traite de l'analyse des données client d'une entreprise, avec un focus sur plusieurs aspects :
- Clustering des clients.
- Visualisation des corrélations entre différentes variables.
- Analyse de la répartition des clients par niveau d'éducation.

Le but de ce notebook est d'explorer les données, les visualiser, et extraire des insights utiles pour des décisions commerciales basées sur les comportements des clients.

## Structure

Le projet est structuré en plusieurs étapes majeures :

### 1. **Chargement et préparation des données**
   - Les données sont chargées depuis un fichier Excel nommé **`Camp_Market.xlsx`**.
   - Les données sont nettoyées et transformées, y compris la conversion des colonnes en valeurs numériques et le calcul de nouvelles variables (dépenses totales, âge, etc.).

### 2. **Clustering des clients**
   - Un algorithme de **KMeans** est utilisé pour regrouper les clients en clusters basés sur leurs comportements d'achat.
   - Les clusters sont ensuite analysés et visualisés pour mieux comprendre les différences entre les groupes de clients.

### 3. **Visualisation des corrélations**
   - Une matrice de corrélation est générée pour les variables numériques, permettant d'analyser les relations entre différentes variables comme les dépenses (`Spent`), le revenu (`Income`), et d'autres.
   - Un graphique en barres est utilisé pour visualiser la corrélation entre `Spent` et d'autres variables.

### 4. **Répartition des clients par niveau d'éducation**
   - Un histogramme est créé pour visualiser la répartition des clients selon leur niveau d'éducation, aidant à identifier les catégories les plus représentées.

## Installation

### Prérequis
Avant d'exécuter ce projet, assurez-vous que vous avez **Python 3.x** installé, ainsi que toutes les bibliothèques nécessaires listées ci-dessous.

### Installation des dépendances

1. Clonez ce dépôt sur votre machine locale :
   ```bash
   git clone <lien_du_depot>

2. Installez les dépendances requises avec pip :
   ```bash
   pip install pandas matplotlib scikit-learn

3. Ouvrez le fichier Jupyter Notebook Code_Graphiques.ipynb avec Jupyter Lab ou Jupyter Notebook 
   ```bash
   jupyter notebook Code_Graphiques.ipynb

## Utilisation

- Exécutez chaque cellule du notebook pour reproduire l'analyse et les visualisations.
- Vous pouvez adapter le notebook à vos propres données ou ajuster les seuils de clustering et les visualisations pour répondre à vos besoins spécifiques.

## Bibliothèques utilisées

Les bibliothèques Python suivantes sont utilisées dans le notebook :
- pandas : pour la manipulation des données.
- matplotlib : pour les visualisations graphiques.
- scikit-learn : pour l'algorithme de clustering KMeans et l'analyse des corrélations.

## Résultats et insights

### Prérequis
- Les clients sont regroupés en plusieurs clusters. Chaque cluster est visualisé et comparé pour identifier des schémas de dépenses et de comportements des clients.

### Corrélations
- La variable Spent (dépenses) est corrélée avec plusieurs autres variables, permettant de mieux comprendre les facteurs influençant les habitudes de dépenses des clients.

### Répartition par éducation
- La répartition par niveau d'éducation permet d'identifier les niveaux d'instruction les plus représentés parmi les clients, fournissant des informations précieuses pour les efforts de ciblage marketing.

## Conclusion

Ce projet offre une vue d'ensemble claire de l'analyse des données clients à l'aide de techniques de clustering et de visualisation. Il permet d'identifier des segments de clientèle distincts et de comprendre les relations entre diverses caractéristiques des clients. Il constitue une base solide pour des analyses plus approfondies ou des applications marketing spécifiques.
