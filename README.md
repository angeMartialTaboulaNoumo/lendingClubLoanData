Auteur: Taboula Noumo Ange Martial

Le projet que j’ai réalisé porte sur la prévision du défaut de crédit, un enjeu majeur pour le secteur financier puisque anticiper le risque de non-remboursement permet de réduire les pertes et d’optimiser la gestion des prêts. J’ai utilisé le dataset Lending Club, initialement composé de plus de 2 millions de lignes, ce qui représentait un volume trop important pour ma puissance de calcul. Pour gérer cette contrainte, j’ai filtré les données sur une période spécifique tout en conservant une représentativité suffisante des cas de défaut.

Mon approche s’est basée sur des réseaux de neurones, afin de capturer des relations complexes entre les variables et d’obtenir des prédictions plus précises que les modèles classiques. Le dataset contient des informations détaillées sur les emprunteurs et leurs prêts : montant, taux d’intérêt, durée, revenus, historique de crédit, et statut du prêt (Fully Paid ou Charged Off).

Le projet a suivi plusieurs étapes clés :

Exploration des données (EDA) : visualisation de la répartition des prêts, corrélations et valeurs aberrantes

Pré-traitement des données : gestion des valeurs manquantes, transformation des variables catégorielles en numériques et normalisation des variables, tout en conservant l’équilibre entre les classes.

Modélisation avec réseaux de neurones : création et entraînement d’un modèle capable de prédire le défaut de manière robuste, avec optimisation des hyperparamètres et évaluation via des métriques adaptées (F1-score, matrice de confusion, la precision  et le recall).

Ce projet m’a permis de développer mes compétences en data cleaning, feature engineering, deep learning et interprétation des modèles, tout en produisant un cas concret de prévision du risque de crédit, directement pertinent pour le secteur bancaire et financier.


Optique d'ameioration:

 *identification des variables ayant le plus d’impact sur le risque de défaut, ce qui fournit des informations concrètes pour la prise de décision. et ameliorer l'experience utilisateur pour une integration dans une application

