[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ibrahim-traore1607/anomalyze-ml/main?urlpath=lab/tree/ANOMALYZE_v2_binder.ipynb)

# ANOMALYZE

Outil pour explorer un dataset CSV et repérer ses anomalies.

## Fonctionnalités
- Chargement d'un fichier CSV et sélection des colonnes numériques
- KMeans avec choix automatique de k (score de silhouette)
- Projection PCA en 2D
- Détection d'anomalies avec Isolation Forest
- Visualisations : clustering, matrice de corrélation, anomalies
- Export des résultats (CSV) et des figures

## Version Binder
`ANOMALYZE_v2_binder.ipynb` permet de tester le projet en ligne en un clic, sans installation.
- **Sans Tkinter** : Binder n'a pas d'écran, la fenêtre ne peut pas s'y afficher. Les paramètres sont des cellules à modifier.
- **Données de démonstration** : le notebook fonctionne dès l'ouverture, sans fichier à fournir.
- **`requirements.txt`** : Binder doit savoir quelles bibliothèques installer.

Les résultats sont les mêmes dans les deux versions : seuls l'interface et l'affichage changent.

## Installation
pip install -r requirements.txt

## Lancement
- En ligne : cliquer sur le badge Binder, puis **Run → Run All Cells**.
- En local (application de bureau) : ouvrir `ANOMALYZE_v2.ipynb` et exécuter toutes les cellules.

Pour utiliser vos données dans Binder : ajouter le CSV au dépôt, puis mettre `FICHIER = "mon_fichier.csv"` dans le notebook.

*Projet Licence 2 Informatique, 2025-2026*
