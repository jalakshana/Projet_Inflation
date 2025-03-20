# Projet_Inflation

# Évolution de l'inflation en France (1990-2024)

## Introduction  

Ce projet analyse l'**évolution de l'inflation en France** entre 1990 et 2024 en se basant sur plusieurs bases de données économiques fournies par l'**INSEE** et **Eurostat**.  
L'objectif est de comprendre les **tendances inflationnistes**, leurs causes et leur impact à travers différentes catégories de produits (énergie, alimentation, biens manufacturés).  
Nous avons également **modélisé et prédit** l'inflation pour 2024 à l'aide du modèle **ARIMA**, et comparé l'évolution des indices de prix à la consommation harmonisé (IPCH) de plusieurs pays européens.

---

## Objectifs  

✔ **Importer et nettoyer les données** relatives à l'inflation en France depuis 1990.  
✔ **Visualiser les tendances de l'inflation** annuelle et mensuelle.  
✔ **Analyser les relations entre l'inflation énergétique, alimentaire et manufacturée.**  
✔ **Modéliser et prédire l'inflation** pour 2024 à l'aide d'un modèle ARIMA.  
✔ **Comparer l'évolution de l'inflation en France avec d'autres pays européens.**  

---

## Technologies utilisées  

**Langage** : Python  
**Bibliothèques** :  
- `pandas` : Analyse et manipulation des données  
- `numpy` : Calculs mathématiques  
- `matplotlib`, `seaborn` : Visualisation  
- `statsmodels` : Modélisation ARIMA  
- `scikit-learn` : Régression et évaluation  

**Sources des Données** :  
- INSEE
- Eurostat

---

## Installation et exécution  

### 1️⃣ **Cloner le dépôt**  
```bash
git clone https://github.com/jalakshana/Projet_Inflation.git
```
2️⃣ **Installer les dépendances Python**
```bash
pip install -r requirements.txt
```
3️⃣ **Ouvrir et exécuter le Notebook**
```bash
jupyter notebook
```

## Analyses réalisées

Visualisation des tendances de l’inflation
* Graphiques de l’évolution annuelle et mensuelle de l'inflation hors tabac, alimentation, énergie et produits manufacturés.
* Impact des événements économiques (ex : crise financière 2008, COVID-19, guerre en Ukraine).

Analyse des relations entre différents types d’inflation
* Régressions linéaires pour tester l’impact de l’inflation énergétique sur les prix alimentaires et manufacturés.
* Corrélations de Spearman et Kendall pour identifier des liens non linéaires.

Modélisation avec ARIMA et prédiction pour 2024
* Détection de la saisonnalité et de la volatilité des séries temporelles.
* Entraînement du modèle ARIMA pour estimer le taux d’inflation en 2024.
* Évaluation du modèle avec l’erreur quadratique moyenne (RMSE).
  
Comparaison internationale
* Évolution de l’IPCH (Indice de prix harmonisé) dans plusieurs pays (France, Allemagne, Belgique, Suisse, etc.).


