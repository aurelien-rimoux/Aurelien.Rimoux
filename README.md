# 📊 Aurélien RIMOUX - Data Analyst Portfolio

👋 Bienvenue sur mon espace GitHub !

Je suis un **Data Analyst** passionné par la transformation des données brutes en informations exploitables et par l'optimisation des processus métier. Mon expertise couvre l'extraction, le nettoyage, l'analyse statistique et la visualisation de données pour soutenir la prise de décision stratégique.

---

## 🛠 Stack Technique

Voici les technologies que j'utilise au quotidien pour mes analyses et mes projets :

| Catégorie | Outils Clés |
| :--- | :--- |
| **Analyse & Langages** | Python (Pandas, NumPy, Scikit-learn), SQL |
| **Visualisation & BI** | Power BI, Tableau, Matplotlib, Seaborn |
| **ETL & DataOps** | Microsoft Fabric (Lakehouse, Data Pipelines), Azure Data Factory, Apify, PhantomBuster |
| **Bases de Données** | PostgreSQL, MySQL, NoSQL (MongoDB) |
| **Versionning & Autre** | Git/GitHub, Excel Avancé |

---

## 🚀 Mes Projets Phares

### 1. ☁️ Projet : Architecture Data Simplifiée avec Microsoft Fabric et Power BI

Mise en place d'une architecture moderne de Business Intelligence de bout en bout, en exploitant les capacités du Lakehouse et du concept "One Copy of Data".

* **Objectif :** Créer un environnement unifié pour l'ingestion, la transformation et la diffusion de données pour le reporting décisionnel.
* **Technologies Utilisées :** **Microsoft Fabric** (Lakehouse, Data Pipelines), **Power BI** , **Scala/Spark**.
* **Architecture :**
    * **Ingestion :** Notebook Fabric et dataflow gen 2 pour connecter et ingérer les données brutes dans le Lakehouse (Bronze Layer).
    * **Transformation :** Notebooks Fabric pour les transformations ELT et la création de tables Fact/Dim (Gold Layers).
    * **Visualisation :** Création d'un Modèle Sémantique et de tableaux de bord Power BI connectés via **Direct Lake** pour une performance maximale.

➡️ **[Détails du Projet ici](https://github.com/aurelien-rimoux/Data-Architecture-Fabric)**


### 2. 📈 Projet : Scraping et Enrichissement de Données LinkedIn pour France Compétences

Un projet visant à automatiser l'acquisition et la fiabilisation des données d'anciens étudiants pour les audits de certification professionnelle.

* **Objectif :** Mesurer le taux d'insertion professionnelle avec une fiabilité des données supérieure à 80% pour les dossiers d'audit (France Compétences).
* **Technologies Utilisées :** **Python**, Pandas, **Apify**, **PhantomBuster**, Excel.
* **Workflow Technique :**
    *  **Préparation :** Extraction des clés (Nom, Prénom, École) depuis le fichier client source.
    *  **Acquisition :** Recherche des liens **LinkedIn** via PhantomBuster, puis **Scraping** des données complètes via Apify.
    *  **Traitement Python :** Nettoyage des données (déduplication, formatage) et **application des règles métier** (classification des postes, validation de l'ancienneté).
    *  **Livrable :** Export d'un fichier Excel final enrichi et structuré pour le reporting.

➡️ **[Détails du Projet ici](https://github.com/aurelien-rimoux/Scraping-et-enrichissement-de-donnees-LinkedIn)**

---


---

## 🔗 Contact & Réseaux

N'hésitez pas à me contacter pour discuter de mes projets ou d'opportunités en analyse de données !

* **[LinkedIn](https://www.linkedin.com/in/aurelien-rimoux)**
* **[Email](aurelien.rimoux.pro@gmail.com)**

---
*Développé avec la passion de la donnée. Merci de votre visite !*
