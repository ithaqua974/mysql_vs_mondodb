# veille du 27/04/2020

## mysql vs mondodb

les différences entre les deux

### 1 MySQL

**MySQL** est un sysème de gestion de base de donnéesss relationnelles.
comme les autres sytèmes de ce type, **MySQL** stock les données dans des tables et utilise un langage de requêtes structurés (sql) pour base de données.
Lorsque les développeurs MySQL doivent accéder aux données d'une application, ils fusionnent les données de plusieurs tables dans un processus appelé jointure.
Dans MySQL, vous prédéfinissez votre schéma de base de données et définissez des règles pour régir les relations entre les champs de vos tables.

### 2 MongoDB

**MongoDB** est une base de données de type NoSQL qui stock les données dans un document similaire à un fichier **JSON**.
Les documents stockent ensemble les informations connexes et utilisent le langage de requête MongoDB (**MQL**) pour y accèder.
Les champs peuvent varier d'un document à l'autre - il n'est pas nécessaire de déclarer la structure des documents au système, car les documents sont auto-descriptifs.
Facultativement, la validation de schéma peut être utilisée pour appliquer des contrôles de gouvernance des données sur chaque collection.


## le MCD

MCD pour modèle conceptuel de données est la représentation la plus abstraite des données d'un système d'information.
Les données sont représentées sous forme d'entités et d'associations entre entité.

Une entité est ensemble d'éléments de même nature. 
Une association est un ensemble de liens de même nature entre élément d'ensembles.

Les entités et associations sont les briques essentielles de réalisation d'un MCD. Ces briques essentielles sont complétées par:

- Les attributs des entités
- Les types de données des attributs
- Les cardinalités des associations
- Les contraintes implicites et explicites
- ...


