# Analyse des Champs Lexicaux & NLP

Ce projet est une plateforme de traitement du langage naturel (NLP) conçue pour l'analyse de corpus textuels, l'extraction de motifs syntaxiques et la visualisation de données.

---

## Installation Complète 

Pour configurer l'intégralité du projet (environnement, dépendances, modèles spaCy et module PyMotifs), ouvre ton terminal à la racine du dossier et copie-colle cette séquence :

```bash
# 1. Création et activation de l'environnement, installation des libs, du modèle spaCy et de PyMotifs
python3.12 -m venv .venv && \
source .venv/bin/activate && \
pip install pandas spacy gensim matplotlib scikit-learn ipykernel && \
python -m spacy download fr_core_news_sm && \
cd PyMotifs && pip install . && cd ..
```

## Organisation du Repository
Test_naturaliste.ipynb : Notebook principal contenant le code d'analyse et les graphiques.

Corpus_textes/ : Dossier de stockage des fichiers textes à analyser.

PyMotifs/ : Module local pour l'extraction de motifs (installé en mode éditable).

.gitignore : Fichier de configuration pour exclure .venv/, __pycache__ et les fichiers système Mac du suivi Git.


## Stack Technique
Langage : Python 3.12 (pour la stabilité et les performances)

NLP : spaCy (Tokenisation & Parsing), Gensim (Topic Modeling), PyMotifs (Extraction de motifs syntaxiques)

Data Science : Pandas, Scikit-learn

Visualisation : Matplotlib et seaborn