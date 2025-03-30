# 🚀 README - Détection de Phishing par URL

## 📝 Description
Ce projet vise à classer les URLs comme étant légitimes ou de phishing à l'aide de modèles de machine learning. Le notebook inclut l'analyse des données, l'entraînement et l'évaluation de plusieurs modèles pour trouver celui offrant la meilleure précision.

## 📂 Contenu du projet
- `phishing.ipynb` : Notebook contenant l'analyse et le modèle de détection.

## 🤖 Modèles Utilisés
Plusieurs modèles de machine learning ont été testés pour évaluer leur performance dans la classification des URLs :
- 🌲 **Random Forest** : Facile à interpréter et performant sur des données variées.
- 🌳 **Decision Tree** : Rapide mais souvent moins précis.
- ⚡ **XGBoost** : Modèle puissant et optimisé pour la performance.
- 🔍 **Grid Search** a été utilisé pour optimiser les hyperparamètres.

Tous les modèles ont donné de bons résultats en termes de précision. Cependant, la sélection finale a été basée sur la taille du modèle ainsi que le temps d'entraînement et de test. **XGBoost** a été retenu comme le meilleur compromis entre performance, rapidité et légèreté.
