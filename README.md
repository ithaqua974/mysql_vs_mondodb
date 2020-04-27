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

**MCD** pour modèle conceptuel de données est la représentation la plus abstraite des données d'un système d'information.
Les données sont représentées sous forme d'entités et d'associations entre entité.

Une entité est ensemble d'éléments de même nature. 
Une association est un ensemble de liens de même nature entre élément d'ensembles.

Les entités et associations sont les briques essentielles de réalisation d'un MCD. Ces briques essentielles sont complétées par:

- Les attributs des entités
- Les types de données des attributs
- Les cardinalités des associations
- Les contraintes implicites et explicites
- ...

Un modèle conceptuel de données (**MCD**) est réalisé pour représenter les données d'un système d'information.

## API REST

**API** signifie Application Programming Interface.

Dans le cas d'une **API** l'interface va être comme une sorte télécomande pour que votre application web puisse interagir avec un service qui vous offre une ressource

Les **API REST** sont basées sur HTTP

Les API REST imitent la façon dont le web lui-même marche dans les échanges entre un client et un serveur. Une API REST est :

- Sans état

- Cacheable (avec cache = mémoire)

- Orienté client-serveur

- Avec une interface uniforme

- Avec un système de couche

- Un code à la demande (optionnel)


## la CLI

**CLI** pour command line interface, qui comme son nom l'indique est une interface qui utilise un terminal sur votre ordinateur et des ligne de commande pour interagir avec un système.

Par exemple, quand vous utilisez le gestionaire de paquets NPM vous utilisé un cli et vous faites des ligne de commande pour installer les paquets dont vous avez besoin pour votre application web.
ou encore git bash et la cli pour interagir avec git.


## ORM

Un mapping objet-relationnel (en anglais object-relational mapping ou ORM) est un type de programme informatique qui se place en interface entre un programme applicatif et une base de données relationnelle pour simuler une base de données orientée objet.
Ce programme définit des correspondances entre les schémas de la base de données et les classes du programme applicatif.
On pourrait le désigner par là, « comme une couche d'abstraction entre le monde objet et monde relationnel ».
Du fait de sa fonction, on retrouve ce type de programme dans un grand nombre de frameworks sous la forme de composant ORM qui a été soit développé, soit intégré depuis une solution externe.

## langage objet



## aplication hybride

