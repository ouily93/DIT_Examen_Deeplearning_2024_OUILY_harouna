# DIT_Examen_Deeplearning_2024_OUILY_harouna
Notre projet vise à mettre en place un modèle de reconnaissance Automatique de la Parole (ASR) et suivi d'une analyse de sentiment.

## Mise en place du modèle de reconnaissance analyse de sentiment 
### Présentation des données

Les données utilisées ont été téléchargées sur le site de kaggle https://www.kaggle.com/datasets/djilax/allocine-frenchmovie-reviews. 
Il s'agit de données textuelle en français extriment le sentiment positif ou négative. 

Les données sont constituées de données de d'entrainement (train_dataset_allocine_french) et de test (test_dataset_allocine_french).


### Modèle

Nous avons utilisé un model Bert préhentrainé de huggaing face pour mettre en place notre modèle de classification de sentiment.
Le modèle Bert est connut pour sa performence dans l'analyse de classification des données textuelle.

#### Les paramètres du modèles 

Le Pour avoir un modèle très performent dans l'analyse de sentiment nous avons paramètré le modèl. Les paramètre sont

-Nombre d'EPOCHS qui est égale à 2
- Le taux d'apprentissage (Learning Rate)qui est égale à2e-5
- le BATCH_SIZE qui est égale à 8

  ##### packages utilise
Nous avons utilisé un fichier requirements pour encapsuler tous les package à installé en créant un environnement virtuelle dans Windows PowerShell puis dans VSCODE







