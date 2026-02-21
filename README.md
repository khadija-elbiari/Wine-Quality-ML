# Analyse et Prédiction 

## 📝 Présentation du Projet
Ce projet utilise le dataset "Vinho Verde" pour prédire la qualité du vin rouge (score de 0 à 10) à partir de 11 caractéristiques physico-chimiques.
<img width="1024" height="798" alt="download (2)" src="https://github.com/user-attachments/assets/04628e5e-f22b-4d7f-9f50-21f940f9fc7d" />
<img width="695" height="394" alt="download (1)" src="https://github.com/user-attachments/assets/a5cdde10-d086-430d-9056-092f92d2144f" />

## 🛠️ Méthodologie (Pipeline ML)
Conformément au cahier des charges, le projet suit 4 phases :
1. **Réduction de Dimension :** Utilisation de PCA, t-SNE et NMF pour la visualisation.
2. **Apprentissage Non-Supervisé :** Clustering avec K-Means, Agglomerative Clustering et DBSCAN.
3. **Apprentissage Supervisé :** Comparaison de modèles (SVM, Random Forest, KNN).
4. **MLOps :** Tracking des hyperparamètres et métriques avec **MLflow**.

## 🚀 Comment l'utiliser
1. Cloner le dépôt : `git clone https://github.com/votre-nom/Wine-Quality-ML.git`
2. Installer les dépendances : `pip install -r requirements.txt`
3. Lancer MLflow : `mlflow ui` pour voir les expériences.
## 📊 Résultats (MLflow)
Après comparaison des modèles via **MLflow** , le modèle **Random Forest** a été sélectionné comme "Champion".
* **Accuracy :** 87.4% (Remplace par ton vrai chiffre)
***Status :** Modèle déployable pour la prédiction de qualité.
## 👤 Auteur
**Khadija ELBIARI**




