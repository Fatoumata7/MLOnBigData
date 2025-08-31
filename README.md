# Projet Spark – Implémentation distribuée de k-NN et Naïve Bayes



## Description
Ce projet explore l’implémentation et l’évaluation de deux algorithmes classiques de machine learning – **k-Nearest Neighbors (k-NN)** et **Naïve Bayes** – dans l’écosystème **Apache Spark**.  
L’objectif est de comparer trois approches : **RDD**, **DataFrame** et **Spark ML**, selon trois dimensions principales :  
- **Précision (accuracy)**  
- **Temps d’exécution**  
- **Scalabilité** en fonction du volume de données et du parallélisme.  

Les expériences sont menées sur le dataset **Poker Hand**, un benchmark classique pour les tâches de classification.  



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
- **Python 3.8+**
- **Apache Spark (pyspark)**
- **Jupyter Notebook**
- Librairies Python : `pandas`, `matplotlib`



## Exécution
1. Cloner le dépôt :
   ```bash
   git clone <url-du-repo>
   cd projet-spark-knn-naivebayes
    ```

2. Lancer Jupyter Notebook :
   ```bash
   jupyter notebook
   ```
3. Exécuter les notebooks disponibles dans le dossier [`code/`](code/).


##  Résultats

* Comparaison entre **RDD**, **DataFrame** et **Spark ML**
* Analyse de la **scalabilité** (impact du nombre de partitions et de la taille du dataset)



## Auteurs

* **Pénélope Millet**
* **Fatoumata Wadiou**
