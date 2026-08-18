La prolifération des cyberattaques, notamment à travers le phishing et la distribution de malwares, représente une menace croissante pour la cybersécurité. Dans ce contexte, la détection précoce et fiable des URLs malveillantes est devenue une priorité stratégique. 
Les cybercriminels exploitent souvent des techniques d’obfuscation complexes pour dissimuler leurs intentions malicieuses, rendant les méthodes classiques de filtrage insuffisantes.

Ce projet a pour objectif de mettre en place une approche d’apprentissage automatique pour la classification des URLs en deux classes : légitimes ou malveillantes. L’étude explore différentes méthodes classiques et profondes (deep learning) pour améliorer la précision 
de détection, en s’appuyant sur un dataset riche en caractéristiques extraites des URLs.

Le dataset utilisé comporte plus de 6,7 millions de lignes et 61 colonnes, chacune représentant une caractéristique spécifique d’une URL. Ces caractéristiques sont regroupées en plusieurs catégories : informations générales, structure de l’URL, analyse du domaine, présence 
de mots-clés sensibles, mesures statistiques (entropie, distances de Hamming), etc. La colonne label représente la classe cible : 1 pour les URLs malveillantes, 0 sinon.
