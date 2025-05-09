# Révision – Régression Linéaire & Logistique (From Scratch)

Ce projet regroupe deux parties : une **régression linéaire multiple** appliquée à un dataset de voitures, et une **régression logistique binaire** appliquée à un test auditif. L’objectif est d’implémenter tous les modèles **depuis zéro** (sans utiliser `scikit-learn`).

## 📁 Repository

GitHub : [Regression-Mixte-Car-Hearing-FromScratch](https://github.com/Labrini-Ouiam/Regression-Mixte-Car-Hearing-FromScratch.git)

---

## 🔹 Partie 1 : Régression Linéaire Multiple

**Dataset utilisé :** `CarPrice_Assignment.csv`  
**Objectif :** Prédire le **prix** d’une voiture à partir de ses caractéristiques.

### 🧪 Scénarios :
1. Régression sur les **caractéristiques numériques uniquement**
2. Régression en ajoutant la variable **catégorielle `fueltype`** (motorisation)

### 📊 Méthodologie :
- Prétraitement des données (standardisation, encodage)
- Implémentation du modèle linéaire :
  - Fonction coût (MSE)
  - Descente de gradient
- Évaluation : Erreur quadratique moyenne (RMSE), visualisation des prédictions

---

## 🔹 Partie 2 : Régression Logistique Binaire

**Dataset utilisé :** `hearing_test.csv`  
**Objectif :** Prédire l’**aptitude auditive** (0 ou 1) selon :
- `age`
- `physical_score`

### 🎯 Méthodes :
1. **Frontière de décision linéaire**
2. **Frontière de décision non linéaire** (features polynomiales)

### 📌 Étapes :
- Nettoyage et normalisation des données
- Implémentation from scratch :
  - Fonction sigmoïde
  - Fonction coût (log-loss)
  - Descente de gradient
- Visualisation des frontières de décision
- Évaluation avec la précision (accuracy)

---

## 🛠️ Technologies Utilisées

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

Aucune bibliothèque de machine learning (comme `scikit-learn`) n’est utilisée pour les modèles.

---

## 📦 Contenu du Dépôt

- `Linear_Regression_CarPrice.ipynb` : Régression linéaire multiple
- `Logistic_Regression_HearingTest.ipynb` : Régression logistique binaire
- `CarPrice_Assignment.csv` : Dataset des voitures
- `hearing_test.csv` : Dataset test auditif

---

## 👩‍💻 Auteur

**Labrini Ouiam**  

---

> Pour toute question ou suggestion, veuillez ouvrir une issue ou soumettre un pull request.
