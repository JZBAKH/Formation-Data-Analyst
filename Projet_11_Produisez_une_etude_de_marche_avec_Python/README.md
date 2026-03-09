# 🐔 Projet 11 : Produisez une étude de marché avec Python

### 📄 Contexte du projet

La Poule qui Chante, entreprise française productrice de volaille, souhaite exporter ses produits à l'international.  
*Analyser les données mondiales (FAO) pour identifier des groupes de pays potentiels où exporter des produits de volaille, en utilisant des techniques de classification non supervisée.*

### 🎯 Objectifs de la mission
1. **Préparation des données :** Récupérer, nettoyer et consolider les données de la **FAO** et de la **Banque Mondiale**.
2. **Analyse exploratoire :** Étudier les corrélations entre les variables pour sélectionner les indicateurs pertinents.
3. **Segmentation (Clustering) :**
   * Réduire les dimensions via une **ACP**.
   * Appliquer les méthodes **K-Means** et **CAH** pour regrouper les pays ayant des profils similaires.
   * Analyser les centroïdes pour caractériser chaque cluster.
4. **Recommandation :** Sélectionner les clusters les plus attractifs et valider le choix par une **analyse PESTEL** des contraintes et opportunités.


### 📂 Contenu du dossier

1.  * `Zbakh_Jason_1_preparation_nettoyage_analyse_exploratoire_082025.ipynb` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_11_Produisez_une_etude_de_marche_avec_Python/Zbakh_Jason_1_preparation_nettoyage_analyse_exploratoire_082025.pdf) <br> 
      Notebook contenant le code de nettoyage des données, la gestion des valeurs nulles et l'export du fichier final.

2.  * `Zbakh_Jason_2_clustering_visualisations_082025.ipynb` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_11_Produisez_une_etude_de_marche_avec_Python/Zbakh_Jason_2_clustering_visualisations_082025.pdf) <br> 
      Notebook contenant l'analyse en composantes principales (ACP), les algorithmes de clustering (K-Means, CAH) et les visualisations.

3.  * `Zbakh_Jason_3_presentation_082025.pptx` : [PDF](https://raw.githubusercontent.com/JZBAKH/Formation-Data-Analyst/main/Projet_11_Produisez_une_etude_de_marche_avec_Python/Zbakh_Jason_3_presentation_082025.pdf) <br>
      Support de présentation résumant la méthodologie, l'analyse PESTEL et les recommandations stratégiques.

---

### 🛠 Compétences Techniques (Hard Skills)
* **Data Cleaning (Pandas) :** Préparation des données issues de la FAO, gestion des valeurs manquantes et fusion des différents jeux de données (Population, Disponibilité alimentaire, Commerce).
* **Réduction de dimension (ACP) :** Application de l'Analyse en Composantes Principales (PCA) pour réduire le nombre de variables et visualiser les données multidimensionnelles.
* **Clustering (Scikit-learn) :** Segmentation des pays via des algorithmes non supervisés : **K-Means** et Classification Ascendante Hiérarchique (**CAH**).
* **Analyse de performance :** Détermination du nombre optimal de clusters à l'aide de la méthode du coude et du score de silhouette.

### 🧠 Compétences Générales (Soft Skills)
* **Analyse Stratégique :** Réalisation d'une analyse **PESTEL** pour évaluer l'environnement macro-économique et légal des marchés visés.
* **Synthèse :** Sélection de groupes de pays pertinents basés sur des critères objectifs (importations, stabilité, population) pour la direction.
* **Visualisation :** Création de dendrogrammes et de plans factoriels pour illustrer la répartition des pays.

*Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*