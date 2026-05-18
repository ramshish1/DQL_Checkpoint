# 📊 Projet SQL : Phase DQL (Data Query Language)

Bienvenue dans le dossier dédié à la phase d'interrogation de données (DQL) du système d'information sur la participation des salariés.

## 📝 Objectif du Point de Contrôle

L'objectif de ce point de contrôle est de pratiquer l'écriture de requêtes SQL (`SELECT`, `JOIN`, `GROUP BY`, `HAVING`, etc.) pour extraire et analyser les données à partir de la base de données créée lors des phases précédentes (DDL et DML). 
Ces requêtes permettent d'obtenir des informations précieuses sur les employés, les départements, les projets et leurs relations, afin de faciliter la prise de décision.

## 🔍 Requêtes DQL Implémentées

Le fichier SQL présent dans ce dossier (`SQLQuery4.sql`) contient les requêtes répondant aux problématiques suivantes :

1. **Employés multi-projets** : Récupérer les noms des employés affectés à plus d'un projet, incluant le nombre total de projets pour chacun d'eux.
2. **Projets par département** : Lister les projets gérés par chaque département, avec le nom du département et le nom de son responsable.
3. **Équipe du projet "Refonte du site web"** : Afficher les noms des employés travaillant sur le projet de refonte web ("Refonte du site web"), ainsi que leur rôle spécifique.
4. **Département le plus peuplé** : Identifier le département comptant le plus grand nombre d'employés, en incluant le nom du département, le nom du manager et le nombre total d'employés.
5. **Employés hautement rémunérés** : Extraire les noms et postes des employés gagnant un salaire supérieur à 60 000, avec le nom de leur département.
6. **Effectif par projet** : Calculer le nombre d'employés affectés à chaque projet, en affichant le titre du projet.
7. **Synthèse des rôles** : Présenter un résumé des rôles des employés sur les différents projets (nom de l'employé, titre du projet et rôle).
8. **Masse salariale par département** : Calculer la dépense salariale totale pour chaque département, incluant le nom du département et le nom du manager.

## 🚀 Exécution

Pour tester ces requêtes :
1. Assurez-vous d'avoir exécuté au préalable les scripts de création (DDL) et d'insertion de données (DML).
2. Ouvrez et exécutez le script `SQLQuery4.sql` dans votre environnement SQL (SQL Server Management Studio, DBeaver, etc.).

## 📁 Fichiers
- `SQLQuery4.sql` : Script contenant l'ensemble des requêtes d'analyse de données (DQL).

---
*Projet réalisé pour valider les compétences en interrogation et analyse de données SQL (DQL).*
