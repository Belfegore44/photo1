---
title: Cantine
publishDate: 2023-06-23 00:00:00
img: /assets/children.png
img_alt: Symfony ,Boostrap
description: |
  creation d'un site d'inscription pour comptabilisé le nombre de jours avec le prix des repas pris par l'enfant
tags:
  - symfony
  - Dev
  - User Testing
---


## framework Symfony

Symfony est un framework PHP puissant et populaire largement utilisé pour développer des applications web robustes et évolutives. Sa construction repose sur plusieurs étapes clés qui garantissent une structure solide et cohérente.

 <a href="https://symfony.com/">Symfony</a> 

### installation de symfony
La première étape dans la construction de Symfony est l'installation du framework lui-même. Cela peut être fait en utilisant Composer, un gestionnaire de dépendances PHP. Une fois installé, Symfony fournit une structure de fichiers bien organisée qui comprend des répertoires tels que "src" pour le code source, "config" pour la configuration, et "templates" pour les vues.



### Les entités

La deuxième étape consiste à définir les entités de l' application Cantine. Les entités sont des classes qui représentent les objets métier de votre application, comme les utilisateurs, enfant, etc. Vous pouvez définir les propriétés et les relations entre les entités à l'aide d'annotations ou de fichiers de configuration.


#### Migrations

Ensuite, on peut générer les migrations. Les migrations permettent de créer et de mettre à jour la structure de la base de données en fonction des modifications apportées aux entités. Symfony facilite cette tâche en utilisant Doctrine, un ORM (Object-Relational Mapping) intégré, qui permet de travailler avec la base de données de manière orientée objet.

#### Controllers ,twig, http
Une fois la base de données prête, le développement des contrôleurs et des routes commence. Les contrôleurs gèrent les requêtes HTTP et déterminent les actions à effectuer, tandis que les routes associent les URL aux contrôleurs et aux actions correspondantes.

Pour le rendu des templates, Symfony utilise le moteur Twig, qui facilite la création de l'application. Des variables et des boucles sont utilisées pour générer du contenu dynamique dans les templates.
