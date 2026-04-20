# Analyse des champs lexicaux sur les Goncourt

Ce projet explore les champs lexicaux dominants dans un corpus de romans des frères Goncourt à l’aide d’outils de traitement automatique des langues (NLP) en Python.

L’objectif est de repérer, comparer et interpréter les grandes zones lexicales du corpus à partir d’une chaîne de traitement comprenant la préparation des textes, la vectorisation et la modélisation thématique.

## Objectifs du projet

- segmenter un corpus littéraire en unités comparables ;
- nettoyer et lemmatiser les textes ;
- faire émerger des champs lexicaux dominants ;
- comparer plusieurs approches de topic modeling ;
- visualiser la répartition des thèmes selon les œuvres.

## Contenu du dépôt

Le dépôt contient principalement les fichiers suivants :

- `Test_CL_goncourt_300.ipynb` : notebook d’exploration et de tests autour de la segmentation en unités de 300 mots ;
- `Test_Final_Goncourt.ipynb` : notebook principal avec la version finale de l’analyse ;
- `README.md` : présentation du projet ;
- `.gitignore` : exclusions Git.

## Méthodologie générale

Le pipeline d’analyse repose sur les étapes suivantes :

1. constitution du corpus ;
2. segmentation des textes en unités de taille fixe ;
3. prétraitement linguistique avec Python ;
4. vectorisation du corpus ;
5. modélisation thématique ;
6. interprétation des champs lexicaux obtenus ;
7. visualisation des résultats.

## Approche retenue

Le projet s’appuie sur une démarche de NLP appliquée à un corpus littéraire.  
Les expérimentations ont porté sur plusieurs méthodes de modélisation thématique, avec une attention particulière portée à la lisibilité et à l’interprétabilité des résultats.

La logique générale du projet est la suivante :

- prétraitement des textes ;
- extraction d’unités lexicales pertinentes ;
- modélisation des thèmes ;
- comparaison des résultats selon les œuvres ;
- lecture interprétative dans une perspective littéraire.

## Environnement technique

- **Langage** : Python 3.12
- **Format principal** : Jupyter Notebook
- **Bibliothèques principales** :
  - pandas
  - spaCy
  - gensim
  - matplotlib
  - scikit-learn
  - ipykernel

## Installation

Depuis la racine du projet :

```bash
python3.12 -m venv .venv
source .venv/bin/activate
pip install pandas spacy gensim matplotlib scikit-learn ipykernel
python -m spacy download fr_core_news_sm
```

# Lancer le projet

Une fois l’environnement installé :

```bash
source .venv/bin/activate
jupyter notebook
```
Puis ouvrir :

* Test_CL_goncourt_300.ipynb pour les essais intermédiaires ;
* Test_Final_Goncourt.ipynb pour la version finale.

## Résultats attendus

Le projet permet de :

* faire émerger des champs lexicaux dominants dans le corpus ;
* comparer leur poids d’une œuvre à l’autre ;
* visualiser la structure thématique globale du corpus ;
* appuyer une interprétation littéraire à partir d’indicateurs quantitatifs.

## Limites

Cette analyse reste exploratoire.
Les champs lexicaux obtenus correspondent à des regroupements statistiques de termes et non à des thèmes littéraires parfaitement stabilisés. Leur interprétation suppose donc un retour constant aux textes et au contexte d’étude.

# Auteur

Morgan Richard

Dépôt GitHub

Projet disponible ici :
https://github.com/NagromLeBG/Analyse-champs-lexicaux-sur-les-Goncourt￼
