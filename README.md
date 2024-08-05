# MNIST Hybrid Classifier

Ce projet implémente un classificateur hybride pour le jeu de données MNIST, combinant un réseau de neurones et un modèle k-NN (k plus proches voisins) pour améliorer la précision de la classification des chiffres manuscrits.

## Description

Le classificateur hybride utilise deux approches différentes pour la reconnaissance des chiffres manuscrits :

1. Un réseau de neurones simple
2. Un modèle k-NN (k plus proches voisins)

Les prédictions de ces deux modèles sont ensuite combinées en utilisant un vote majoritaire pour produire une prédiction finale.

## Dépendances

Ce projet utilise les bibliothèques Python suivantes :

- NumPy
- scikit-learn
- TensorFlow
- Keras
- SciPy

## Installation

Pour installer les dépendances nécessaires, exécutez :

```
pip install numpy scikit-learn tensorflow scipy
```

## Utilisation

1. Chargez et prétraitez les données MNIST.
2. Entraînez le réseau de neurones.
3. Entraînez le modèle k-NN.
4. Combinez les prédictions des deux modèles.
5. Évaluez les performances du modèle hybride.

## Structure du code

Le code est organisé comme suit :

1. Importation des bibliothèques nécessaires
2. Chargement et prétraitement des données MNIST
3. Définition et entraînement du réseau de neurones
4. Définition et entraînement du modèle k-NN
5. Combinaison des prédictions
6. Évaluation des performances

## Résultats

Le script affiche les précisions pour :
- Le réseau de neurones seul
- Le modèle k-NN seul
- Le modèle hybride



