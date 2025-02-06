# Databricks-Accidents-Project

Ce Repository "Databricks-Accidents-Project" a été créer pour le rendue de notre projet "examen". 
Ce Repository ce compose d'un fichier README.md et de notre notebook "Modelisation" au format dbc.
## 1. Travail en binôme sur machine 

L’objectif de ce projet est de créer un modèle qui permet de prédire la gravité d’un accident, en fonction de plusieurs informations sur cet accident.
Nous nous sommes inspirés du tutoriel d'Ilyes TALBI. 

Pour ce projet nous utilisons des données  issues de "data.gouv.fr".
  - carac.csv nous donne des caractéristiques sur les accidents
  - lieux.csv recense des données sur les lieux des accidents
  - veh.csv donne des informations sur les véhicules impliqués
  - vict.csv donne des informations sur les victimes


A la fin de ce projet nous pouvons dire que le meilleur modèle est : Decision Tree (arbre de décision) avec accuracy = 0.612820 et f1-score=0.596473
