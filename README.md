# Nettoyage de Données – Customer Call List

## Description du Projet

Ce projet présente un processus de **nettoyage et de préparation de données** réalisé avec **Python et la bibliothèque Pandas** dans un notebook Jupyter.

Le dataset contient une liste de clients avec leurs coordonnées. Cependant, les données présentent plusieurs problèmes courants que l'on retrouve souvent dans les bases de données réelles :

- valeurs manquantes
- formats incohérents
- doublons
- colonnes inutiles
- erreurs de saisie

L'objectif de ce projet est de **nettoyer et structurer les données afin de les rendre exploitables pour l'analyse ou pour une utilisation commerciale (contact client).**

---

## Objectifs

Les principales étapes du nettoyage sont :

- suppression des doublons
- suppression des colonnes inutiles
- nettoyage des noms de famille
- standardisation des numéros de téléphone
- séparation de l'adresse en plusieurs colonnes
- gestion des valeurs manquantes
- normalisation des valeurs catégorielles (Yes / No)
- suppression des contacts qui ne souhaitent pas être appelés
- suppression des lignes sans numéro de téléphone

---

## Dataset

Le dataset contient les colonnes suivantes :

- First Name
- Last Name
- Address
- Phone Number
- Paying Customer
- Do Not Contact

---

## Technologies utilisées

- Python
- Pandas
- Jupyter Notebook

---

## Structure du Projet

