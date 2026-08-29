#  Detection des URLs malveillantes avec Machine Learning

> Détection et classification automatique des URLs malveillantes à l'aide de techniques de Machine Learning et de Deep Learning.

##  Présentation

Face à la multiplication des attaques de **phishing**, de la distribution de malwares et des techniques d'obfuscation, l'identification automatique des URLs malveillantes constitue un enjeu important en cybersécurité.

Ce projet vise à développer un système capable de **classifier automatiquement une URL comme légitime ou malveillante** à partir de caractéristiques extraites de son contenu et de sa structure.

Différentes approches de **Machine Learning classique et de Deep Learning** sont étudiées afin d'identifier les modèles les plus performants pour cette tâche de classification.

##  Objectifs

- Analyser les caractéristiques des URLs.
- Prétraiter et explorer un dataset de grande dimension.
- Identifier les caractéristiques pertinentes pour la détection.
- Entraîner plusieurs modèles de Machine Learning.
- Étudier des approches de Deep Learning.
- Comparer les performances des différents modèles.
- Évaluer leur capacité à détecter les URLs malveillantes.

##  Dataset

Le dataset contient plus de **6,7 millions d'URLs** et **61 caractéristiques**.

Les caractéristiques couvrent notamment :

-  Informations générales sur l'URL
-  Structure et longueur de l'URL
-  Caractéristiques du domaine
-  Mots-clés et caractères suspects
-  Caractéristiques statistiques
-  Entropie
-  Distance de Hamming
-  Autres indicateurs comportementaux et structurels

### Variable cible


label = 0 → URL légitime

label = 1 → URL malveillante


## Approche méthodologique

L'approche adoptée repose sur une chaîne de traitement permettant de transformer les caractéristiques des URLs en modèles de classification capables de distinguer les URLs légitimes des URLs malveillantes.

```text
Dataset
   │
   ▼
Exploration et analyse des données
   │
   ▼
Prétraitement des données
   │
   ▼
Sélection / préparation des caractéristiques
   │
   ▼
Séparation des données
   │
   ├── Données d'entraînement
   └── Données de test
   │
   ▼
Entraînement des modèles
   │
   ├── Machine Learning
   └── Deep Learning
   │
   ▼
Évaluation des performances
   │
   ▼
Comparaison des modèles
   │
   ▼
Sélection du modèle le plus performant
