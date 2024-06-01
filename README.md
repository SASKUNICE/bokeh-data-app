# Bokeh Data App

Cette application Bokeh visualise des données provenant de l'ensemble de données Avito Car. Elle permet d'analyser diverses caractéristiques des voitures, telles que la puissance fiscale, le type de carburant, le kilométrage, et plus encore.

## Contenu du dépôt

- `README.md` : Description de l'application.
- `data_visualization.ipynb` : Notebook Jupyter contenant le code de l'application et l'analyse des données.
- `bokeh_app.py` : Script Python contenant le code de l'application Bokeh.
- `data/` : Dossier contenant le fichier de données `AvitoCarDataset_ready2Viz.csv`.

## Visualisations

1. **Puissance fiscale par année modèle** : Analyse de la distribution de la puissance fiscale en fonction de l'année du modèle.
2. **Répartition des types de carburant par marque** : Répartition des différents types de carburant utilisés par chaque marque.
3. **Heatmap de la boîte de vitesses par ville et prix** : Visualisation de la relation entre la boîte de vitesses, la ville et le prix des voitures.
4. **Nombre de portes par modèle** : Distribution du nombre de portes par modèle de voiture.
5. **Heatmap des systèmes de sécurité par marque** : Comparaison des normes de sécurité entre les différentes marques.
6. **Kilométrage moyen par marque** : Analyse du kilométrage moyen des voitures par marque.
7. **Prix moyen par marque** : Analyse du prix moyen des voitures par marque.
8. **Nombre d'occurrences de la marque la plus fréquente par ville** : Analyse des marques les plus populaires dans différentes villes.
9. **Répartition des états par marque** : Distribution des états des voitures (Bon, Très Bon, Excellent) par marque.

## Instructions

### Prérequis

- Python 3.x
- Bokeh
- Pandas

### Installation

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/votre_nom_utilisateur/bokeh-data-app.git
   cd bokeh-data-app
