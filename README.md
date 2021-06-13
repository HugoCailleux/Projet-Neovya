# Neovya

Vous trouverez dans ce repository l'ensemble des notebooks du projet NEOVYA

**Notebook 1**: Neovya_dataexploration.ipynb

- Présentation & explication des jeux de données


**Notebook 2**: Neovya_mapping_sensors.ipynb

- Visualisation des capteurs et sélection des capteurs présents sur la N230


**Notebook 3:** Projet-Neovya-Feature-Engineering-général-sur-la-n230.ipynb

- Enrichissement de notre dataset avec des données météo et ajout des jours de la semaine


**Notebook 4:** Projet-Neovya-tri-des-colonnes-météo-par-classification.ipynb

- Sélection des variables pertinentes par features importance et permutation importance


**Notebook 5 à 9: Prédictions de l'état du trafic (Congestionné "1" et non congestionné "0") avec différents modèles de classification**

- Modèle Naive Bayes

[Projet-Neovya-Modèle-Modèles-Bayésiens.ipynb]

- Modèle de séries temporelles

[Projet-Neovya-modèle-Etude-des-séries-temporelles.ipynb]

- Modèle KNN

[Projet-Neovya-Modèle-KNN.ipynb]

- Modèle de Random Forest Classifier

[Projet-Neovya-Modèle-Random-Forest.ipynb]

- Modèle de régression logistique

[Projet-Neovya-Modèle-Régression.ipynb]

**Notebook 10:** Projet-Neovya-Agrégation-des-modèles-X_valid.ipynb

Après avoir prédit la congestion sur un capteur avec 5 modèles différents (**voir Notebook 5 à 9**), l'objectif de ce Notebook est d'agréger ensemble les modèles précédents pour pouvoir obtenir un résultat global et le plus fiable statistiquement. Trois techniques d'agrégations ont été utilisées à savoir:

- Agrégation par probabilité
- Agrégation par vote
- Agrégation par forêt aléatoire:
