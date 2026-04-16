# Analyse macro-économique orientée risque – Portugal

##  Objectif du projet

Ce mini-projet vise à analyser l’évolution d’indicateurs macroéconomiques (inflation et chômage) et leur interprétation dans une logique de risque.

À partir de données publiques Eurostat, l’objectif est de construire un jeu de données propre et exploitable, puis d’identifier les dynamiques économiques pouvant impacter le niveau de risque d’un pays (ici : le Portugal).

Ce type d’analyse constitue une première étape dans les approches de risk management, notamment pour la surveillance macroéconomique ou la construction de scénarios de stress.


##  Données utilisées

Les données proviennent exclusivement de **sources publiques**, principalement :

- **Eurostat** (statistiques officielles européennes)
  - Inflation
  - Chômage
  - Indicateurs macro-économiques agrégés

Les données sont utilisées à des fins **pédagogiques et analytiques**.



##  Étapes du pipeline

Le projet suit les étapes suivantes :

- Collecte de données macro-économiques (Eurostat)
- Nettoyage et préparation des données
- Structuration pour l’analyse
- Analyse exploratoire avec une approche orientée risque
- Synthèse des résultats (logique reporting / Excel)



## Technologies utilisées

- Python  
- Jupyter Notebook  
- Pandas / NumPy  



##  Structure du dépôt

- `macro_risk_pipeline.ipynb` : notebook principal
- `data_raw/` : données brutes
- `.ipynb_checkpoints/` : fichiers temporaires Jupyter



##  Contexte du projet

L’analyse met en évidence l’évolution conjointe du chômage et de l’inflation, indicateurs clés pour évaluer la situation macroéconomique.

Dans un contexte de gestion des risques, ces dynamiques peuvent être utilisées pour détecter des signaux de détérioration économique et alimenter des analyses plus avancées (stress tests, modèles de risque de crédit, etc.).



##  Auteur

Carole  ALAIN
Projet personnel – Data analysis & risk orientation
