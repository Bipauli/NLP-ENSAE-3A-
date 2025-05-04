# NLP-ENSAE-3A

## [Mini-projet] Détection de Fake News

Ce projet vise à entraîner et évaluer des modèles de classification pour détecter les fake news à partir de textes.

### Jeux de données

Les deux jeux de données utilisés proviennent de Kaggle :

- **ISOT Dataset**  
  [Fake News Detection Datasets (ISOT)](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets)

- **Kaggle Fake or Real News**  
  [Fake or Real News Dataset](https://www.kaggle.com/datasets/jillanisofttech/fake-or-real-news)

### Description

Le projet inclut :
- Prétraitement des textes (analyse des données, vectorisation avec TF-IDF et Word2Vec)
- Entraînement de modèles de régression logistique
- Utilisation de validation croisée et de splits train/test
- Évaluation des performances (accuracy, precision, recall, f1-score, confusion matrix)
- Évaluation de la généralisabilité des modèles 

---

### Pour exécuter le projet

1. Cloner le dépôt
2. Installer les dépendances  
   ```bash
   pip install -r requirements.txt
