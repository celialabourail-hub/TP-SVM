# Organisation du projet

- `src/` : scripts et code source Python
- `data/` : jeux de données
- `results/` : résultats, exports, rapports
- `figures/` : images, graphiques
- `tests/` : scripts de test

## Lancer le projet

1. Installer les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
2. Exécuter les scripts depuis `src/`.

## Dépôt GitHub

Ce projet est versionné sur : https://github.com/celialabourail-hub/TP-SVM# TP-SVM
Ce TP a pour objectif de découvrir et expérimenter les SVM à travers différents jeux de données (artificiels, Iris, reconnaissance de visages).

# TP-SVM : Structure du projet

Voici l’arborescence recommandée pour ce projet SVM :

```
TP-SVM/
├── data/                # Jeux de données bruts ou traités
├── figures/             # Graphiques, images, captures d'écran
├── results/             # Résultats finaux, sorties de scripts
├── src/                 # Scripts sources (.py, .qmd, .ipynb)
├── tests/               # Scripts de test éventuels
├── README.md            # Présentation du projet
├── .gitignore           # Fichiers à ignorer par Git
├── requirements.txt     # Dépendances Python (optionnel)
└── archive/             # Archives, anciens fichiers, brouillons
```

## Détail des dossiers
- **data/** : jeux de données utilisés pour l’entraînement ou les tests.
- **figures/** : toutes les images et graphiques générés ou insérés dans le rapport.
- **results/** : résultats finaux, PDF générés, sorties de scripts.
- **src/** : scripts Python, fichiers Quarto, notebooks, etc.
- **tests/** : scripts de test pour valider le code.
- **archive/** : versions obsolètes, brouillons, fichiers à conserver mais non utilisés.

## Conseils Git
- Ajoute un fichier `.gitignore` pour ignorer les fichiers temporaires, les dossiers `__pycache__`, etc.
- Documente les dépendances dans `requirements.txt` si tu utilises des packages Python spécifiques.

N’hésite pas à adapter cette structure selon tes besoins !
