# Rush5 Project

## Description

Ce projet traite de l'analyse des données client d'une entreprise, en mettant l'accent sur plusieurs aspects tels que le clustering des clients, la visualisation des corrélations entre variables, et l'analyse de la répartition des niveaux d'éducation. Ce notebook a pour but d'explorer ces données, de les visualiser et d'extraire des insights utiles.

## Structure

Le projet est structuré en plusieurs étapes majeures, chacune visant à accomplir une tâche spécifique d'analyse des données :

### 1. **Clustering des clients**
   - Le clustering des clients est effectué à l'aide de l'algorithme **KMeans**. Le but est de regrouper les clients en différents clusters basés sur des caractéristiques pertinentes.
   - Les clusters sont ensuite utilisés pour calculer des statistiques agrégées et visualiser les différences entre eux.
   
### 2. **Visualisation des corrélations**
   - Une matrice de corrélation est calculée pour les différentes variables numériques du DataFrame. Cela permet de comprendre les relations entre la variable **Spent** (montant dépensé) et d'autres variables importantes.
   - Un graphique en barres est utilisé pour visualiser la corrélation de la variable **Spent** avec les autres variables.

### 3. **Répartition des clients par niveau d'éducation**
   - Un histogramme est généré pour montrer la distribution des clients selon leur niveau d'éducation. Cela permet d'identifier quels niveaux d'éducation sont les plus courants parmi les clients de l'entreprise.

## Installation

1. Clonez ce dépôt sur votre machine locale.
   ```bash
   git clone <lien_du_depot>

2. Ouvrez le fichier Jupyter Notebook Rush5.ipynb avec Jupyter Lab ou Notebook :
    ```bash
    jupyter notebook Rush5.ipynb

### Utilisation
    - Exécutez chaque cellule du notebook pour reproduire l'analyse.
    - Vous pouvez adapter le notebook en fonction de vos propres données ou besoins d'analyse.

### Bibliothèques utilisées
Les bibliothèques Python suivantes sont utilisées dans le notebook :

- pandas : pour la manipulation des données.
- matplotlib : pour les visualisations graphiques.
- scikit-learn : pour l'algorithme de clustering KMeans et l'analyse des corrélations.

## Résultats et insights
### Clustering
- Les clients sont regroupés en n clusters. Chaque cluster est visualisé et comparé pour identifier des schémas de dépenses et de comportements clients.

### Corrélations
La variable Spent est corrélée avec plusieurs autres variables, permettant de comprendre les facteurs influençant les dépenses des clients.

### Répartition par éducation
La répartition des niveaux d'éducation montre quelles catégories d'éducation sont les plus représentées parmi les clients, fournissant des informations utiles pour le ciblage marketing.

## Conclusion

Ce projet fournit une vue d'ensemble claire de l'analyse des données clients à l'aide de techniques de clustering et de visualisation. Il peut être utilisé pour identifier des segments de clientèle et comprendre les relations entre les différentes caractéristiques des clients.

