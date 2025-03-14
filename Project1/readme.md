# Projet 3 : Analyse des facteurs influençant les performances commerciales

## Objectif
Le but de ce projet est d'analyser les interactions entre les différents produits, les performances régionales et les marges afin d'optimiser la stratégie commerciale d'une entreprise. Nous allons identifier les facteurs clés qui influencent les ventes et les profits pour proposer des recommandations stratégiques.

### Problématique
Avec une demande croissante et une concurrence féroce sur le marché, un supermarché géant cherche à comprendre quels produits, régions, catégories et segments de clients ils devraient cibler ou éviter. Ce projet permet de réaliser des analyses exploratoires sur un jeu de données afin de dégager des insights stratégiques.

### Objectifs principaux :
- Analyser les relations entre les variables qualitatives (ex. : Segments, Catégories) et quantitatives (ex. : Ventes, Profits).
- Détecter des facteurs clés à travers des analyses bivariées (corrélations, tableaux croisés, comparaisons de moyennes).
- Visualiser ces relations à travers des graphiques avancés (scatter plots, boxplots, heatmaps).
- Proposer des recommandations stratégiques basées sur les résultats obtenus.

## Dataset

Le jeu de données contient les informations suivantes :

- **Row ID** : Identifiant unique pour chaque ligne.
- **Order ID** : Identifiant unique de la commande.
- **Order Date** : Date de la commande du produit.
- **Ship Date** : Date d'expédition du produit.
- **Ship Mode** : Mode d'expédition choisi par le client.
- **Customer ID** : Identifiant unique du client.
- **Customer Name** : Nom du client.
- **Segment** : Segment auquel appartient le client.
- **Country** : Pays de résidence du client.
- **City** : Ville de résidence du client.
- **State** : État de résidence du client.
- **Postal Code** : Code postal du client.
- **Region** : Région du client.
- **Product ID** : Identifiant unique du produit.
- **Category** : Catégorie du produit commandé.
- **Sub-Category** : Sous-catégorie du produit commandé.
- **Product Name** : Nom du produit.
- **Sales** : Montant des ventes du produit.
- **Quantity** : Quantité de produits commandés.
- **Discount** : Remise appliquée.
- **Profit** : Profit ou perte générée par la vente.

## Compétences à acquérir

- **Analyse bivariée descriptive** :
  - Analyser les corrélations entre les variables quantitatives (ex. : Ventes et Profits).
  - Réaliser des comparaisons de moyennes entre différentes catégories (ex. : Profits selon les régions).
  - Créer des tableaux croisés dynamiques pour observer les relations entre variables qualitatives et quantitatives.
  
- **Visualisation avancée** :
  - Utilisation de graphiques **scatter plots** pour visualiser la relation entre deux variables quantitatives (ex. : Ventes vs Profits).
  - **Boxplots** pour observer les distributions des ventes et des profits en fonction des segments ou des régions.
  - **Heatmap** pour représenter visuellement les corrélations entre plusieurs variables.

- **Interprétation des relations** :
  - Identifier les facteurs clés qui influencent les performances commerciales.
  - Fournir des recommandations stratégiques pour optimiser la stratégie de vente en fonction des résultats d'analyse.

## Structure du projet

Le projet est structuré comme suit :

- **Data Exploration** : Exploration initiale du jeu de données, nettoyage des données et préparation pour l'analyse.
- **Exploratory Data Analysis (EDA)** : Analyse des relations entre les différentes variables à l'aide de statistiques descriptives et de visualisations.
- **Modélisation** : Construction d'un modèle de régression pour prédire les ventes ou les profits en fonction des caractéristiques des produits et des clients.
- **Insights** : Présentation des conclusions tirées des analyses et des recommandations stratégiques.

## Technologies utilisées

- **Langage de programmation** : Python (ou R)
- **Bibliothèques Python** : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Outils de visualisation** : Matplotlib, Seaborn pour les graphiques et heatmaps

## Conclusion

Ce projet vise à utiliser des techniques d'analyse de données et de modélisation statistique pour fournir des insights précieux qui permettront à l'entreprise d'optimiser ses performances commerciales. Les résultats peuvent guider les décisions sur les produits à privilégier, les régions à cibler et les stratégies de prix à adopter.

---

Si vous avez des questions ou des suggestions, n'hésitez pas à ouvrir une *issue* ou à soumettre une *pull request*.

## Auteurs
- **Marel AGONGLO**


## Licence
Ce projet est sous licence MIT.
