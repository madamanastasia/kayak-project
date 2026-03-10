# 🧳 Planifiez votre voyage – Projet Data Engineering

## 📌 Présentation

Ce projet met en place un pipeline de données permettant de collecter et d’analyser des informations touristiques pour plusieurs villes françaises.

L’objectif est de démontrer des compétences pratiques en :

- Web scraping  
- Intégration d’API  
- Structuration de données  
- Analyse avec SQL  
- Visualisation  

L’ensemble du projet est organisé de manière claire afin de distinguer la phase de collecte, la phase de stockage des données et la phase d’analyse.

---

# 🛠 Technologies utilisées

- Python  
- requests  
- pandas  
- BeautifulSoup  
- SQLite / SQL  
- Jupyter Notebook  

---

# 📂 Structure du repository

```
kayak_project/
├── notebooks/
│   ├── weather.ipynb
│   ├── hotels.ipynb
│   └── sql_analysis.ipynb
├── data/
│   ├── cities.csv
│   ├── weather_daily.csv
│   └── hotels.csv
├── database/
│   └── kayak.db
└── README.md
```

---

# 🧩 Description des fichiers

## 📓 weather.ipynb

Notebook dédié à la collecte des données météorologiques :

- Appels API pour récupérer les données météo
- Structuration des réponses JSON
- Nettoyage des données
- Export vers `weather_daily.csv`

Ce notebook montre l’intégration d’une API REST et la transformation des données reçues.

---

## 📓 hotels.ipynb

Notebook consacré au web scraping :

- Extraction des informations hôtels
- Parsing du HTML
- Nettoyage et structuration
- Export vers `hotels.csv`

Ce notebook démontre la capacité à collecter des données non structurées et à les transformer en données exploitables.

---

## 📓 sql_analysis.ipynb

Notebook d’analyse SQL :

- Création des tables relationnelles
- Import des fichiers CSV dans la base
- Jointures entre villes, météo et hôtels
- Requêtes analytiques (agrégations, filtres, tri)
- Génération de visualisations

Il illustre l’utilisation du SQL pour exploiter les données collectées.

---

## 📄 cities.csv

Contient la liste des villes étudiées ainsi que leurs coordonnées GPS.

---

## 📄 weather_daily.csv

Données météorologiques collectées via API, structurées et nettoyées.

---

## 📄 hotels.csv

Données issues du scraping :

- Nom  
- Prix  
- Note  
- Description  
- Localisation  

---

## 🗄 kayak.db

Base de données SQLite locale utilisée pour :

- Stocker les tables relationnelles  
- Exécuter les requêtes SQL  
- Centraliser les données avant analyse  

Cette base permet de simuler un environnement de base de données relationnelle dans un contexte local.

---

# 🏁 Conclusion

Ce projet démontre la capacité à collecter, structurer et analyser des données à travers un workflow complet, en utilisant Python et SQL dans un environnement reproductible.

---

 # 👤 Auteur

Anastasiia Belosludtseva
