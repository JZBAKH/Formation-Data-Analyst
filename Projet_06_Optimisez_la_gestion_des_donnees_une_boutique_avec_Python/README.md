# 🍷 Projet 6 : Optimisez la gestion des données d'une boutique

### 📄 Contexte du projet

Unification des données **ERP** (stock) et **CMS** (ventes web) pour Bottleneck via **Python/Pandas**. Calcul du **chiffre d'affaires** et détection d'**outliers** par la méthode de l'écart interquartile (**IQR**).

### 🎯 Objectifs de la mission
1. **Rapprochement ETL :** Fusion des exports **ERP** et **Web** via une table de liaison (**merge** Pandas).
2. **Calcul du CA :** Analyse des ventes et calcul du chiffre d'affaires total (**143k€**).
3. **Détection des anomalies :** Identification des **outliers** (31 produits) par la méthode **IQR** et analyse de leur cohérence métier.

### 📂 Contenu du dossier

1.  * `Zbakh_Jason_1_notebook_022025.ipynb` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_06_Optimisez_la_gestion_des_donnees_une_boutique_avec_Python/Zbakh_Jason_1_notebook_022025.pdf) <br> 
      Notebook Python pour l'importation, le nettoyage, la jointure des tables et l'analyse exploratoire.

2.  * `Zbakh_Jason_2_presentation_022025.pptx` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_06_Optimisez_la_gestion_des_donnees_une_boutique_avec_Python/Zbakh_Jason_2_presentation_022025.pdf) <br>
      Support de présentation résumant la méthodologie de rapprochement et l'analyse des résultats (CA de 143k€).

---

### 🛠 Compétences Techniques (Hard Skills)
* **Python/Pandas :** Nettoyage de données, gestion des clés primaires et **fusion** (**merge**) de tables hétérogènes.
* **Analyse de données :** Calcul du **chiffre d'affaires** et indicateurs de vente.
* **Statistiques descriptives :** Détection des **outliers** par la méthode de l'écart interquartile (**IQR**).
* **Data Visualization :** Représentation des distributions (**boxplots**) et corrélations (**scatterplots**) pour identifier les écarts de prix.

### 🧠 Compétences Générales (Soft Skills)
* **Rigueur :** Vérification minutieuse de l'unicité des clés et de la qualité du rapprochement entre sources déconnectées.
* **Esprit d'analyse :** Interprétation des écarts de prix pour distinguer les erreurs techniques des spécificités métier (vins premium).
* **Synthèse :** Présentation structurée des résultats financiers et des anomalies détectées à la direction.

*Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*