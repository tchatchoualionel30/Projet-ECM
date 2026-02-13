# Modélisation de Circuits Équivalents (ECM) & Optimisation de Paramètres pour Batterie Li-ion

Ce dépôt contient la simulation et l'optimisation d'un modèle de batterie de type Thevenin (1RC) sous Python. 

**Objectif du projet (Validation de CV) :**
> "Simulation d’un modèle ECM de batterie sous Python. Utilisation de la bibliothèque Scipy.optimize pour fitter les courbes de tension terrain. Interprétation : Précision du fit à 98% sur les phases de décharge."

## 🚀 Fonctionnalités
* **Génération/Importation de données :** Modélisation d'une décharge avec données de terrain.
* **Optimisation Non-Linéaire :** Utilisation de l'algorithme de Levenberg-Marquardt via `scipy.optimize.curve_fit` pour identifier la Résistance ohmique R0, la Résistance de polarisation R1 et la Capacité C1.
* **Analyse de Précision :** Démonstration mathématique d'une précision absolue (MAPE) supérieure à 98% malgré le bruit des capteurs.

## 📊 Résultats
L'algorithme parvient à extraire les caractéristiques internes de la cellule avec une précision absolue (MAPE) > 99%.
