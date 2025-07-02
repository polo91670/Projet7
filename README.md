## API de Scoring Crédit – Projet 7 parcours Data Scientist de OpenClassrooms
Cette API permet de prédire la probabilité de défaillance de remboursement d’un client à partir de ses caractéristiques. Elle a été développée dans le cadre du Projet 7 du parcours Data Scientist de OpenClassrooms : **"Implémenter un modèle de scoring"**.

## Objectifs du projet
- Déployer un modèle de scoring dans une API.
- Utiliser un **seuil de probabilité optimal** pour automatiser la décision d'acceptation/de refus.
- Exposer les résultats via une interface simple

## Technologies utilisées
- notebook Jupyter	6.3.0
- python 3.12.4
- fastAPI 0.115.12
- scikit-learn 1.4.2
- pandas 2.2.2
- joblib 1.4.2
- pytest 8.3.4
- mlflow 2.22.0
- shap 0.46.0
- joblib 1.4.2
- streamlit 1.45.1
- evidently 0.7.8
- imbalanced-learn 0.12.3

## Structure du projet concernant la modelisation
data_drift_report.html # Rapport Evidently entre application_test.csv (nouveaux jeu de données) et application_train.csv (données qui a servi à l'entrainement du modèle)<br>
VANYIALU_Paul_notebook_analyse+simulations_052025.ipynb # Notebook avec l'ingénierie des données et les simulations des modèles<br>
README.md<br>

## Auteur
Projet réalisé dans le cadre du parcours **Data Scientist - OpenClassrooms**

- Nom : *VA NYIA LU*
- Prénom : *PAUL*
- Contact : *paul.va-nyia-lu@cetelem.fr*