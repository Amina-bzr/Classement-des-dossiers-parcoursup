# README - Modèle de Régression Linéaire avec Ponderations

## Description
Ce projet vise à développer un modèle de régression linéaire pour déduire les pondérations optimales des différentes matières et autres facteurs influençant la moyenne générale pondérée et la celle du 1er semestre en L1 MIPI des candidats. Le modèle utilise un ensemble de données comprenant diverses caractéristiques des candidats ainsi que leurs performances dans différentes matières.

## Structure du Dataset
Le dataset utilisé comprend les caractéristiques suivantes des candidats :

1. **Caractéristiques des Candidats** :
   - Moyennes dans différentes matières
   - Bonus attribués
   - Profil du candidat
   - Type d'établissement
   - Type de formation
   - Série/Domaine/Filière
   - Sections linguistiques
   - etc.

## Objectif du Modèle
L'objectif principal de ce modèle est de prédire la moyenne du 1er semestre de la L1 MIPI obtenu par un candidat en fonction de ses caractéristiques et performances dans différentes matières en terminale et en première. En utilisant la régression linéaire, on cherche à déterminer les pondérations optimales à accorder à chaque matière et facteur pour determiner au mieux la moyenne générale pondérée du lycée et ainsi prédire la moyenne du 1er semestre de la L1.

## Développement du Modèle
Le modèle sera développé en suivant les étapes suivantes :

1. **Exploration des Données** :
   - Analyse des caractéristiques et performances des candidats
   - Identification des corrélations entre les variables

2. **Prétraitement des Données** :
   - Gestion des valeurs manquantes
   - Encodage des variables catégoriques
   - Gestion des valeurs aberrantes
   - Normalisation/Standardisation des données

3. **Construction du Modèle de Régression Linéaire personalisé** :
   - Ajout de paramètres supplémentaires
   - Redéfinition des méthodes fit, predict, etc.
   - Intégration de la logique de calcul des moyennes pondérées

5. Évaluation du Modèle Final
