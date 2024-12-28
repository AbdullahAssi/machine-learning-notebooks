# Machine Learning Notebooks

A collection of Jupyter notebooks covering core machine learning techniques — from data preprocessing and classic supervised models to clustering, neural networks and reinforcement learning. Several algorithms (K-Means, backpropagation, streaming clustering) are implemented from scratch with NumPy.

## Contents

| Area | Notebook | Highlights |
|------|----------|------------|
| Python | [Python Fundamentals](python-basics/python_fundamentals.ipynb) | Primes, palindromes from text, Disarium numbers |
| Preprocessing | [Employee Data Cleaning & Scaling](data-preprocessing/employee_data_cleaning_and_scaling.ipynb) | Missing values, one-hot encoding, Min-Max & Standard scaling |
| Supervised | [Decision Tree: Gini vs Entropy](supervised-learning/decision-tree/decision_tree_iris_gini_vs_entropy.ipynb) | GridSearchCV tuning, Graphviz tree visualization |
| Supervised | [Naive Bayes vs Decision Tree](supervised-learning/naive_bayes_vs_decision_tree_categorical.ipynb) | Categorical features, label encoding |
| Supervised | [Naive Bayes with Stratified K-Fold](supervised-learning/naive_bayes_iris_stratified_kfold.ipynb) | Cross-validated evaluation on Iris |
| Supervised | [KNN Breast Cancer Classification](supervised-learning/knn_breast_cancer_classification.ipynb) | SelectKBest, ROC-AUC, F1, confusion matrix |
| Supervised | [Random Forest vs AdaBoost](supervised-learning/random_forest_vs_adaboost_iris.ipynb) | Bagging vs boosting comparison |
| Supervised | [SVM Breast Cancer Classification](supervised-learning/svm_breast_cancer_with_pca.ipynb) | Linear SVM, PCA visualization, ROC curve |
| Neural Networks | [Backpropagation from Scratch](neural-networks/backpropagation_from_scratch.ipynb) | 2-2-1 sigmoid network in NumPy |
| Unsupervised | [K-Means from Scratch](unsupervised-learning/kmeans_from_scratch.ipynb) | NumPy implementation with visualization |
| Unsupervised | [Hierarchical Clustering](unsupervised-learning/hierarchical_clustering_linkage_comparison.ipynb) | Linkage methods compared via dendrograms |
| Unsupervised | [Streaming K-Means](unsupervised-learning/streaming_kmeans_outliers_concept_drift.ipynb) | Online clustering, outlier & concept drift detection |
| Reinforcement | [Q-Learning on CartPole](reinforcement-learning/q_learning_cartpole.ipynb) | Tabular Q-learning with state discretization |

### Featured project

**[Adult Income Clustering](projects/adult-income-clustering/adult_income_clustering.ipynb)** — end-to-end unsupervised analysis of the UCI Adult dataset: EDA, feature selection, K-Means and DBSCAN, evaluated with Silhouette and Davies-Bouldin scores. *(Team project.)*

The [`drafts/`](drafts) folder holds earlier iterations and alternate versions.

## Getting started

```bash
git clone <this-repo-url>
cd <repo-folder>
pip install -r requirements.txt
jupyter notebook
```

Most notebooks use datasets bundled with scikit-learn. Local data files sit next to the notebook that uses them. The Decision Tree notebook also needs the [Graphviz](https://graphviz.org/download/) system package to render trees.

## Tech stack

Python · NumPy · pandas · scikit-learn · SciPy · Matplotlib · Seaborn · OpenAI Gym
