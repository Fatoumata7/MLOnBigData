# Projet : K-NN et Naïve Bayes avec MapReduce



## Description

Ce projet s’intéresse à l’implémentation et à l’évaluation de deux algorithmes emblématiques de l’apprentissage automatique – **k-Nearest Neighbors (k-NN)** et **Naïve Bayes** – en utilisant **PySpark** et le paradigme **MapReduce**.

L’étude vise à comparer trois modes d’exécution : **RDD**, **DataFrame** et **Spark ML**, selon trois axes principaux :
* **Précision des résultats (accuracy)**
* **Performance temporelle (temps d’exécution)**
* **Capacité de passage à l’échelle (scalabilité)**

Les implémentations s’appuient sur les travaux de Jesus Maillo (*A MapReduce-based k-Nearest Neighbor Approach for Big Data Classification*) et de Songtao Zheng (*Naïve Bayes Classifier: A MapReduce Approach*).
Les expérimentations sont réalisées sur le jeu de données **Poker Hand**, un benchmark de référence pour les problèmes de classification.



## Arborescence du projet
```
├── .gitignore
├── code
│   ├── mapreduce workflow for knn.ipynb        # Implémentation k-NN (RDD, DataFrame, Spark ML)
│   ├── mapreduce workflow for naive bayes.ipynb # Implémentation Naïve Bayes
│   ├── poker-hand-testing.data                 # Données de test
│   ├── poker-hand-training-true.data           # Données d’entraînement
│   └── poker-hand.names                        # Description des données
├── rapport\_millet\_wadiou.pdf                   # Rapport académique complet
└── visualizations
├── knn scalability accuracy.png            # Graphique : évolution accuracy selon la taille du dataset
└── knn scalability time exec.png           # Graphique : évolution temps d'exécution selon la taille du dataset
````



## 🚀 Prérequis
- **Python 3.9+**
- **Apache Spark (pyspark)**
- **Jupyter Notebook**
- Librairies Python : `pandas`, `matplotlib`



## Exécution
1. Cloner le dépôt :
   ```bash
   git clone https://github.com/Fatoumata7/MLOnBigData.git
   cd MLOnBigData
    ```

2. Lancer Jupyter Notebook :
   ```bash
   jupyter notebook
   ```
3. Exécuter les notebooks disponibles dans le dossier [`code/`](code/).


##  Résultats

* Comparaison entre **RDD**, **DataFrame** et **Spark ML**
* Analyse de la **scalabilité** (impact du nombre de partitions et de la taille du dataset)



## Informations

* Auteurs : **Pénélope Millet** & **Fatoumata Wadiou**
* Dernière mise à jour le : 31 août 2025