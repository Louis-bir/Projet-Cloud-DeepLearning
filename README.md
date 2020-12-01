# Projet : Déploiement d'un modèle dans le cloud

**Autor :** Louis BIRENHOLZ  
**Date :** 10/07/2020  
**Durée totale du projet :** 80 heures  
**Vidéo du projet** : https://www.youtube.com/watch?time_continue=1981&v=FMrlZQLUvBI&feature=emb_title  

## Background du projet :

Pour ce projet, nous cherchons à venir en aide à une start-up de **l'AgriTech** voulant développer des solutions innovantes pour la récolte de fruit. 
Cette solution passe par la création d'une application permettant de **classer des fruits** en différentes catégories via une photo. Cette application permettrait de sensibiliser le grand public à la biodiversité des fruits et de mettre en place une première version du moteur de classification des images de fruits.

**Nous cherchons à anticipier le fait que le volume de données va augmenter très rapidement**, ainsi nous travaillerons via des outils **Big Data** pour se préparer au passage à l'échelle. Enfin, nous déploierons ce modèle dans le cloud (**Amazon Web Services**).  

## Key points du projet :

- Travail sur le cloud d'Amazon. Utiliation des services **S3** (stockage des données), **EC2** et **EMR** en instanciant sur les serveurs US-EAST-2B.
- Utilisation de **Spark** et implémentation du pipeline en **pyspark** pour anticiper un futur passage à l'échelle.
- Computer Vision : **Transfer Learning** & **Feature Extraction** (ResNet50) via la librairie **SparkDeepLearning**
- Recommandations pour le client pour le moteur de classification (**Scaling horizontale** plutot que vertical en utilisant **Amazon EMR**)
