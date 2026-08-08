# Projet_Classification_Telco
Ce projet consiste à appliquer plusieurs modèles de Machine Learning et Deep Learning sur le dataset Telco
Customer Churn afin de prédire si un client va quitter l’entreprise de télécommunication ou rester.
# 1. Description du Dataset
Le dataset contient des informations sur les clients d’une entreprise de télécommunication.
Les variables représentent les services utilisés, les informations de contrat, les paiements et la variable cible Churn.
# 2. Analyse des Données
Les étapes suivantes ont été réalisées :
- Analyse des dimensions du dataset
- Analyse des types des variables
- Détection des valeurs manquantes
- Étude des distributions des données
- Détection des valeurs aberrantes
# 3. Valeurs Manquantes
La colonne TotalCharges contenait 11 valeurs manquantes.
Ces valeurs ont été remplacées par la médiane à l’aide de SimpleImputer.
# 4. Prétraitement
Les opérations de prétraitement réalisées :
- Suppression de customerID
- Encodage de la variable cible
- One-Hot Encoding des variables catégorielles
- Standardisation des données
- Séparation Train/Test
# 5. Modèles Utilisés
Les modèles appliqués sont :
- KNN
- Decision Tree
- Random Forest
- Réseau de neurones MLP
# 6. Évaluation
Les métriques utilisées :
- Accuracy
- Precision
- Recall
- F1-score
- Matrice de confusion
- Classification report
# 7. Comparaison des Modèles
Le modèle Random Forest a donné les meilleures performances globales.
Le réseau de neurones a également donné de très bons résultats.
# 8. Conclusion
Ce projet a permis de comprendre les différentes étapes d’un projet de Machine Learning :
prétraitement, modélisation, évaluation et comparaison des modèles
