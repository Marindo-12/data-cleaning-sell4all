# Sell4All — Exploration de données clients

## 1. Présentation du projet

L'entreprise **Sell4All**, spécialisée dans la vente de vêtements d'occasion en ligne, souhaite développer une fonctionnalité d'intelligence artificielle permettant de recommander automatiquement des produits à ses utilisateurs. Ce projet consiste à explorer, analyser et nettoyer les données clients disponibles afin de vérifier leur qualité en vue de cette future utilisation.

## 2. Étapes suivies

- **Jour 1 :** Installation de l'environnement (Miniconda, Jupyter, Pandas, Matplotlib), mise en place du dépôt GitHub, lecture du fichier CSV, affichage des 5 premières lignes, résumé technique du dataset (`info()`) et explication de ce résumé dans une cellule Markdown.
- **Jour 2 (demi-journée) :** Calcul des statistiques (moyenne, médiane) sur l'âge et les dépenses clients, calcul bonus de la médiane d'âge par pays, visualisation des dépenses par pays, nettoyage des données (dépenses < 10 €, doublons) et export du fichier nettoyé.

## 3. Fonctionnalités développées

- Lecture du fichier `dataset-sell4all.csv` avec Pandas
- Affichage des 5 premières lignes et d'un résumé technique du dataset (`info()`)
- Calcul de la moyenne et de la médiane des colonnes `Age` et `Customer spendings`
- Calcul bonus de la médiane d'âge par pays
- Visualisation des dépenses clients par pays (graphique à barres)
- Nettoyage des lignes avec moins de 10 € de dépenses et suppression des doublons
- Export des données nettoyées dans `dataset_filtered.csv`

## 4. Difficultés rencontrées et solutions

- Les ressources mentionnées dans le document du brief apparaissaient soulignées et en bleu (comme des liens), mais n'étaient pas cliquables. 

## 5. Mode d'exécution

### Prérequis
- Python (via [Miniconda](https://docs.conda.io/en/latest/miniconda.html))
- Jupyter Notebook
- Bibliothèques : `pandas`, `matplotlib`

### Étapes

1. Cloner le dépôt
   ```bash
   git clone https://github.com/Marindo-12/data-cleaning-sell4all
   cd data-cleaning-sell4all


2. Installer les dépendances
   ```bash
   pip install pandas matplotlib
   ```

3. Lancer Jupyter Notebook
   ```bash
   jupyter notebook
   ```

4. Ouvrir `explo.ipynb` et exécuter les cellules dans l'ordre

## Fichiers du dépôt

| Fichier | Description |
|---|---|
| `explo.ipynb` | Notebook Jupyter contenant l'analyse, le nettoyage et les visualisations |
| `dataset-sell4all.csv` | Données brutes fournies |
| `dataset_filtered.csv` | Données nettoyées (dépenses ≥ 10 €, doublons supprimés) |