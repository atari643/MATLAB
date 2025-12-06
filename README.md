# Template pour TP/TDM Stats

Ce projet est un modèle complet pour réaliser des Travaux Pratiques (TP) ou Travaux Dirigés sur Machine (TDM) de statistiques en utilisant MATLAB.

## Description

Ce template au format MATLAB Live Script (`.mlx`) regroupe les éléments essentiels pour mener à bien une analyse statistique. Il contient :
- Du texte explicatif et des équations.
- Du code MATLAB détaillé et commenté.
- Des figures pour visualiser les résultats (histogrammes, courbes, etc.).
- Des commentaires analytiques sur les résultats obtenus.

Il sert de base pour l'apprentissage des statistiques sous MATLAB, abordant la génération de variables aléatoires, l'estimation de paramètres et les tests d'hypothèses.

## Contenu du projet

Le script `TemplateSTAT.mlx` aborde les thématiques suivantes :

1.  **Initiation aux statistiques sous MATLAB**
    *   Génération de réalisations de loi uniforme.
    *   Utilisation de l'algorithme de Box-Müller pour générer des lois gaussiennes.

2.  **Génération de signaux de test**
    *   Simulation de données selon une loi de Weibull.
    *   Vérification de la représentativité des données (histogrammes, ajustements).

3.  **Estimation de paramètres**
    *   Calcul de l'espérance et de la variance (théorique vs estimée).
    *   Comparaison d'estimateurs : Méthode des Moments (Mmo) vs Maximum de Vraisemblance (MV).
    *   Analyse du biais et de l'Erreur Quadratique Moyenne (EQM).
    *   Comparaison avec la Borne de Cramér-Rao (BCR).

4.  **Détection de signal**
    *   Tracé des courbes de puissance théorique.
    *   Tracé des courbes COR (ROC) estimées.

5.  **Application sur données réelles**
    *   Chargement et analyse du fichier `wind.mat` (vitesse du vent).
    *   Ajustement de loi et Test de Kolmogorov.

## Fichiers

*   `TemplateSTAT.mlx` : Le fichier principal (Live Script) contenant le code et les explications.
*   `wind.mat` : Jeu de données réelles (vitesse du vent) utilisé dans la dernière partie.

## Utilisation

Ouvrez le fichier `TemplateSTAT.mlx` dans MATLAB. Vous pouvez exécuter le code section par section pour visualiser les graphiques et suivre le déroulement de l'analyse statistique.
