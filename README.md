# Classification de commentaires - NLP

Modèle capable d’analyser automatiquement du texte et de le classifier dans plusieurs catégories.


## Table des matières
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Sources](#sources)
- [Utilisation](#utilisation)
- [Auteurs](#auteurs)


## Introduction

Dans le cadre de notre cours de natural language processing à Junia ISEN Lille, il nous a été demandé de créer un modèle de deep learning utilisant de l’embedding et des RNNs, le tout dans un pipeline prennant en entrée une phrase brute et qui effectue tous les traitements pour arriver à une classification.

Le contexte du sujet donné est :
> Pour une entreprise proposant à ses utilisateurs d’écrire des commentaires, il est intéressant de savoir analyser les traces que laissent les utilisateurs sur leur plateforme.

> C’est d’autant plus important car vous pourriez être responsable, autant que ceux qui l’ont écrit, des propos injurieux et toxiques de vos utilisateurs.

> L’application est assez simple, il vous suffit d'entraîner un modèle capable d’analyser automatiquement du texte et de le classifier dans plusieurs catégories.
> Pour chaque commentaire, à vous de déterminer la classe la plus plausible.


## Technologies

Ce projet utilise :
- [Google Colab](https://colab.research.google.com)
- tensorflow: 2.11.0
- nltk: 3.7
- scikit-learn: 1.0.2 
- pandas: 1.3.5
- Python: 3.8.10


## Sources

Le sujet de ce projet nous a été donné par [Morgan Gautherot](https://github.com/MorganGautherot) et utilise les données du [*Toxic Comment Classification Challenge*](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data) qui a eu lieu sur la platforme [Kaggle](https://www.kaggle.com).


## Utilisation

Pour lancer ce projet, il vous suffit de vous rendre sur le fichier [Classification_commentaires_toxiques.ipynb](https://github.com/GatienVilain/Toxic-Comment-classification/blob/2adc41e0e3abb3c873398898ff849a263fa75bc3/Classification_commentaires_toxiques.ipynb) et de cliquer sur **Open In Colab** en haut du fichier. Vous serez alors redirigé sur le site de [*Google Colab*](https://colab.research.google.com) avec le fichier déja ouvert et près à être exécuter.

Une autre option est d’utiliser, *Jupyter Notebook* et de l’éxécuter sur votre propre matériel. Pour cela, je vous laisse cloner ce dépôt et suivre les instructions sur le site de [*Jupyter*](https://jupyter.org/install) pour mettre en place votre environement de travail.


## Auteurs

Ce projet vous est proposé par [Dorian Larouziere](https://github.com/DorianLarouziere) et [Gatien Vilain](https://github.com/GatienVilain).
