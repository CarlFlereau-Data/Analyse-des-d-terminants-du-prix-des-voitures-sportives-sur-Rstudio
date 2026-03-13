**Analyse des déterminants du prix des voitures sportives sur Rstudio**

🎯 Objectif du projet

L’objectif est d’identifier les caractéristiques techniques qui influencent le prix des voitures sportives et de construire un modèle statistique capable d’expliquer ce prix.

L’analyse permet notamment de comprendre :

les relations entre performance et prix

les variables techniques les plus déterminantes

la capacité de ces variables à modéliser le prix des véhicules

🧠 Dataset

Dataset utilisé : Sports Car Prices Dataset (Kaggle)

Ce dataset contient des voitures de sport produites entre 1965 et 2023 avec plusieurs caractéristiques techniques.

Variables principales :

Car Make : constructeur

Car Model : modèle

Year : année

Engine Size : taille du moteur

Horsepower : puissance moteur

Torque : couple moteur

0-60 MPH Time : temps d’accélération

Price : prix du véhicule

Après nettoyage, l’analyse porte sur 419 véhicules issus de 35 constructeurs.

🔬 Méthodologie

L’analyse repose sur plusieurs étapes :

1️⃣ Nettoyage des données

gestion des valeurs manquantes

suppression des doublons

uniformisation des variables

2️⃣ Analyse descriptive

distribution des prix

analyse des performances des véhicules

comparaison entre constructeurs

3️⃣ Tests statistiques

test d’indépendance (Khi²) entre le prix et les caractéristiques techniques

4️⃣ Modélisation

régressions linéaires simples

régression linéaire multiple

Le modèle final explique environ 63 % de la variation du prix des voitures sportives.

📈 Variables influençant le prix

Les variables les plus déterminantes dans le prix sont :

la puissance moteur

la taille du moteur

les performances d’accélération

🛠 Technologies utilisées

R

Analyse statistique

Régression linéaire

Visualisation de données

💡 Apports du projet

Ce projet démontre :

une capacité à analyser un dataset réel

une maîtrise des méthodes statistiques appliquées à la data

une capacité à construire et interpréter un modèle statistique
