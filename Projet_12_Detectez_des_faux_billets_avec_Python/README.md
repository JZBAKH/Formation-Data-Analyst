# 💸 Projet 12 : Détectez des faux billets avec Python

### 📄 Contexte du projet

L'ONCFM souhaite développer un outil de détection automatisée des faux billets.  
*Construction d'un algorithme de classification pour prédire l'authenticité des billets de banque à partir de leurs caractéristiques géométriques.*

### 🎯 Objectifs de la mission
1. **Préparation des données :** Analyser les statistiques descriptives et imputer les valeurs manquantes via une **Régression Linéaire**.
2. **Analyse exploratoire :** Réaliser une **ACP** pour visualiser la séparabilité des classes (Vrais vs Faux).
3. **Modélisation :**
   * Tester une approche non supervisée (**K-Means**) pour observer le clustering naturel.
   * Entraîner une **Régression Logistique** pour la classification supervisée.
4. **Déploiement :** Livrer un programme Python opérationnel pour prédire l'authenticité sur de nouveaux fichiers de production.

### 📂 Contenu du dossier

1.  * `Zbakh_Jason_1_Notebook_analyse_102025.ipynb` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_12_Detectez_des_faux_billets_avec_Python/Zbakh_Jason_1_Notebook_analyse_102025.pdf) <br> 
      Notebook contenant l'analyse exploratoire, l'imputation par régression linéaire, l'ACP et la comparaison des modèles (Régression Logistique vs K-Means).

2.  * `Zbakh_Jason_2_Notebook_application_102025.ipynb` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_12_Detectez_des_faux_billets_avec_Python/Zbakh_Jason_2_Notebook_application_102025.pdf) <br> 
      Notebook d'application permettant de lancer le modèle de données entraîné à l'étape précédente sur le set de données production.

3.  * `Zbakh_Jason_3_Présentation_102025.pptx` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_12_Detectez_des_faux_billets_avec_Python/Zbakh_Jason_3_presentation_102025.pdf) <br>
      Support de présentation résumant la méthodologie, les résultats de l'ACP et la performance du modèle retenu.

---

### 🛠 Compétences Techniques (Hard Skills)
* **Machine Learning (Scikit-learn) :** Entraînement et comparaison de modèles prédictifs : Classification supervisée (**Régression Logistique**) et Classification non supervisée (**K-Means**).
* **Data Cleaning & Imputation :** Traitement avancé des valeurs manquantes via une **Régression Linéaire** pour conserver l'intégrité statistique du jeu de données.
* **Analyse de données (Pandas/Seaborn) :** Exploration des données et visualisations pour comprendre la distribution des dimensions (longueur, hauteur, marges).
* **Réduction de dimension (ACP) :** Utilisation de l'Analyse en Composantes Principales pour visualiser la séparabilité des classes (Vrais vs Faux) sur un plan factoriel.
* **Déploiement :** Création d'un script d'application fonctionnel capable de traiter de nouveaux fichiers de production.

### 🧠 Compétences Générales (Soft Skills)
* **Rigueur méthodologique :** Comparaison des performances des modèles via des matrices de confusion pour sélectionner l'algorithme le plus robuste.
* **Vulgarisation :** Présentation des résultats techniques et des recommandations à une audience métier non-experte.
* **Esprit de synthèse :** Rédaction d'une conclusion argumentée justifiant le choix du modèle final.

*Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*