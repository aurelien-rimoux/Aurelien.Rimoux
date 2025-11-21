# 📊 Aurélien RIMOUX - Data Analyst Portfolio

👋 Bienvenue sur mon espace GitHub !

Je suis un **Data Analyst** passionné par la transformation des données brutes en informations exploitables et par l'optimisation des processus métier. J'ai une affinité particulière pour l'**automatisation des tâches et des processus** répétitifs, afin de garantir un maximum de **gain de temps, de fiabilité et d'efficacité** dans la prise de décision. Mon expertise couvre l'extraction, le nettoyage, l'analyse statistique et la visualisation de données pour soutenir la prise de décision stratégique.

---

## 🛠 Stack Technique

Voici les technologies que j'utilise au quotidien pour mes analyses et mes projets :

| Catégorie | Outils Clés |
| :--- | :--- |
| **Analyse & Langages** | Python (**Pandas**, **Numpy**, **Scikit-learn**), SQL |
| **Visualisation & BI** | Power BI (DAX), Tableau, Matplotlib, Seaborn |
| **ETL & DataOps** | **Microsoft Fabric** (Lakehouse, Data Pipelines) *— Expertise Cloud Moderne* |
| **Acquisition & Web Scraping** | Apify, PhantomBuster |
| **Manipulation de Données** | App Script (GAS), Excel Avancé (Power Query) |
| **Bases de Données & Versionning** | PostgreSQL, MySQL, Hubspot (CRM), Git/GitHub |

---

## 🚀 Mes Projets Phares

### 1. ☁️ Projet : Architecture Data Simplifiée avec Microsoft Fabric et Power BI

**Contexte :** L'architecture existante était instable, les règles métier et transformations étant codées de manière non maîtrisée dans Power Query et le Modèle Sémantique.

Mise en place d'une architecture moderne de Business Intelligence de bout en bout, en exploitant les capacités du Lakehouse et le concept **"One Copy of Data"** pour garantir la gouvernance.

* **Impact Clé :** Centralisation de **100% des règles métier** dans des Notebooks Spark (sorties de Power Query). Consolidation de **+10 sources de données** critiques dans un environnement unique (Lakehouse).
* **Objectif :** Créer un environnement unifié, maîtrisé et fiable pour l'ingestion, la transformation et la diffusion de données pour le reporting décisionnel.
* **Technologies Utilisées :** **Microsoft Fabric** (Lakehouse, Data Pipelines), **Power BI**, **Scala/Spark**.
* **Architecture :**
    * **Ingestion :** Notebook Fabric et dataflow Gen2 pour connecter et ingérer les données brutes dans le Lakehouse (Bronze Layer).
    * **Transformation :** Notebooks Fabric pour les transformations ELT et la création de tables Fact/Dim (Gold Layers) **où sont appliquées les règles métier centralisées**.
    * **Visualisation :** Création d'un Modèle Sémantique et de tableaux de bord Power BI.

➡️ **[Détails du Projet ici](https://github.com/aurelien-rimoux/Data-Architecture-Fabric)**

### 2. 📈 Projet : Scraping et Enrichissement de Données LinkedIn pour France Compétences

**Contexte :** Nécessité d'auditer le taux d'insertion professionnelle des anciens étudiants, tâche manuelle, coûteuse en temps et avec un risque d'erreur important.

Un projet visant à automatiser l'acquisition et la fiabilisation des données d'anciens étudiants pour les audits de certification professionnelle.

* **Impact Clé :** Fiabilité des données garantie **supérieure à 80%** pour les dossiers d'audit (France Compétences). Traitement automatique de **+2000 profils**, réduisant le temps de collecte manuelle de **90%**.
* **Objectif :** Mesurer le taux d'insertion professionnelle avec une fiabilité des données supérieure à 80% pour les dossiers d'audit (France Compétences).
* **Technologies Utilisées :** **Python**, **Apify**, **PhantomBuster**, Excel.
* **Workflow Technique :**
    * **Préparation :** Extraction des clés (Nom, Prénom, École) depuis le fichier client source.
    * **Acquisition :** Recherche des liens **LinkedIn** via PhantomBuster, puis **Scraping** des données complètes via Apify.
    * **Traitement Python :** Nettoyage des données (déduplication, formatage) et **application des règles métier**.
    * **Livrable :** Export d'un fichier Excel final enrichi et structuré pour le reporting.

➡️ **[Détails du Projet ici](https://github.com/aurelien-rimoux/Scraping-et-enrichissement-de-donnees-LinkedIn)**

---

## 🔗 Contact & Réseaux

N'hésitez pas à me contacter pour discuter de mes projets ou d'opportunités en analyse de données, et explorez les autres répertoires pour **plus d'exemples de scripts SQL ou Python** !

* **[LinkedIn](https://www.linkedin.com/in/aurelien-rimoux)**
* **[Email](aurelien.rimoux.pro@gmail.com)**

---
*Développé avec la passion de la donnée. Merci de votre visite !*
