Prédiction des Prix de Diamants avec AdaBoost

Ce projet a pour objectif de prédire les prix des diamants à l'aide de l'algorithme de machine learning AdaBoost. Il a été réalisé dans le cadre d'un exercice pratique en machine learning pour approfondir la compréhension des modèles de boosting appliqués à une tâche de régression.

Objectifs

Appliquer AdaBoost à une tâche de régression pour prédire les prix des diamants.

Explorer et analyser les données (étape EDA - Exploration Descriptive et Analyse).

Construire un pipeline complet de prétraitement des données (nettoyage, encodage, normalisation).

Optimiser les hyperparamètres pour améliorer les performances du modèle.

Fournir des visualisations claires et interpréter les résultats obtenus.

Données

Les données utilisées proviennent d'un jeu de données ouvert comprenant les caractéristiques suivantes :

Carat : Poids du diamant.

Coupe (Cut) : Qualité de la coupe.

Couleur (Color) : Classe de couleur (D à J).

Pureté (Clarity) : Degré de pureté du diamant.

Profondeur (Depth) : Hauteur du diamant en pourcentage.

Table : Largeur relative de la table.

Prix (Price) : Prix en dollars US (variable cible).

Contenu du Projet

1. Exploration et Analyse des Données (EDA)

Analyse statistique des variables (distributions, moyennes, corrélations).

Visualisation des relations entre les variables (scatter plots, heatmaps).

2. Prétraitement des Données

Gestion des valeurs manquantes.

Encodage des variables qualitatives (one-hot encoding).

Normalisation des variables quantitatives pour une meilleure convergence.

3. Modélisation avec AdaBoost

Utilisation d'un DecisionTreeRegressor comme modèle faible.

Optimisation des hyperparamètres principaux (« n_estimators », « learning_rate »).

4. Évaluation des Performances

Calcul des métriques :

MSE (Mean Squared Error) : 285,282.94.

R² (Coefficient de Détermination) : 0.98.

Visualisation des prédictions versus les valeurs réelles.

5. Discussion et Améliorations

Analyse des forces du modèle (précisions élevées, capture des relations complexes).

Limites potentielles (éventuel surapprentissage).

Installation

Pour exécuter ce projet, suivez les étapes ci-dessous :

Clonez le dépôt :

git clone <lien_du_dépôt>

Accédez au dossier :

cd <nom_du_dossier>

Installez les dépendances :

pip install -r requirements.txt

Exécutez le notebook ou les scripts Python.

Structure du Projet

notebooks/ : Contient les notebooks Jupyter pour l'analyse et la modélisation.

scripts/ : Scripts Python pour la prétraitement et la modélisation.

data/ : Dossier contenant les données d'entraînement.

README.md : Documentation du projet.

requirements.txt : Liste des dépendances Python nécessaires.

Livrables

Code Source : Scripts et notebooks pour reproduire les résultats.

Documentation : Fichier README avec des instructions complètes.

Rapport Final : Analyse, méthodologie et résultats.

Auteurs

Hergi DIANGUE DI MOUNGUET

LEVIS JUNIOR

Sous la supervision de : Mr. Burak Civicioglu

Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, de le modifier et de le distribuer avec attribution.

Remerciements

Merci à tous les collaborateurs et superviseurs pour leur soutien dans ce projet.

