# CustomerReviewPreprocessing

Pipeline de préparation, nettoyage, normalisation et vectorisation d'avis clients pour l'analyse automatique des sentiments.

## Overview

Une entreprise souhaite développer un système capable de classer automatiquement les avis clients afin d'identifier leur sentiment.

Les avis sont collectés depuis différentes sources :

- site web ;
- application mobile ;
- formulaire de satisfaction ;
- réseaux sociaux ;
- service client.

La diversité des sources entraîne des problèmes de qualité dans les données : textes vides, doublons, fautes de frappe, différences de casse, caractères spéciaux, emojis, URLs, mentions, répétitions de caractères, textes très courts ou très longs et valeurs manquantes.

Ce projet met en place un pipeline complet de préparation des données textuelles avant leur utilisation dans un modèle de Machine Learning ou de Deep Learning.

---

## Objectives

Le projet couvre les principales étapes de préparation d'un corpus textuel :

- Explorer un corpus de textes.
- Analyser la qualité des données.
- Identifier les valeurs manquantes.
- Détecter les textes vides et trop courts.
- Identifier les doublons.
- Nettoyer les textes.
- Gérer les URLs et mentions.
- Traiter les emojis et caractères spéciaux.
- Uniformiser la casse.
- Normaliser les répétitions de caractères.
- Tokeniser les textes.
- Comparer différentes méthodes de vectorisation.
- Transformer les textes en représentations numériques.
- Préparer un corpus exploitable par un modèle de ML/DL.

---

## Dataset

Le dataset contient des avis clients provenant de plusieurs sources.

Les informations peuvent notamment inclure :

| Colonne | Description |
|---|---|
| `id_avis` | Identifiant de l'avis |
| `date` | Date de publication de l'avis |
| `source` | Source de l'avis |
| `produit` | Produit concerné |
| `texte` | Texte original de l'avis |
| `sentiment` | Catégorie de sentiment |
| `note` | Note attribuée par le client |
| `langue` | Langue du texte |

Le fichier original est stocké dans :

```text
data/smart_reviews_raw.csv


## 📁 Project Structure

CustomerReviewPreprocessing/
│
├── notebooks/
│   └── text_preprocessing.ipynb
│
├── data/
│   ├── smart_reviews_raw.csv
│   ├── smart_reviews_cleaned.csv
│   └── tfidf_matrix.npz
│
└── README.md
```

## ✍️ Auteur

**Harouna MBAYE**
- GitHub : [@harounambaye](https://github.com/harounambaye)
- LinkedIn : [Harouna Mbaye](https://www.linkedin.com/in/harouna-mbaye-088926239/)
- Portfolio :[harouna-mbaye](https://harouna-mbaye.netlify.app/)
- Email : roonmbaye5@gmail.com
