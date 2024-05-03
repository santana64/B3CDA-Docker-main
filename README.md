# B3CDA-Docker-main

﻿# Projet de Gestion de Produits avec Docker

﻿#Description du Projet : 
 
 Ce projet utilise Docker pour conteneuriser une application de gestion de produits, avec pour objectif de fournir une infrastructure portable et reproductible pour le déploiement et le développement de l'application, tout en supportant différents moteurs de base de données.

﻿# Fonctionnalités : 
 Conteneurisation avec Docker : Isolation complète de l'environnement pour éviter les conflits de dépendances. Support multi-base de données : Compatible avec plusieurs systèmes de gestion de base de données pour une flexibilité maximale. Déploiement facile et rapide : Démarrez votre environnement de développement en quelques commandes.

﻿# Prérequis : Docker Docker Compose

﻿# Installation et Démarrage :

Clonage du dépôt Pour obtenir le projet, clonez le dépôt GitHub: git clone https://github.com/santana64/B3CDA-Docker-main 

cd gestion-produits

 # Construction et Lancement des Conteneurs : Construisez les images Docker et lancez les conteneurs :

docker-compose up -d Accès à l'Application

Une fois les conteneurs en fonction, accédez à l'application via : http://localhost:8080

﻿# Configuration : 
 
 Dockerfile : Contient les directives pour construire l'image Docker de l'application PHP. Dockerfile.postgresql : Spécifie les étapes pour construire l'image Docker pour PostgreSQL. docker-compose.yml : Définit les services Docker pour l'application et la base de données.

﻿# Utilisation des Services de Base de Données :
 
 Vous pouvez utiliser le service PostgreSQL configuré pour gérer les données. Les détails de connexion sont spécifiés dans docker-compose.yml.

﻿# Contribution : 
 Les contributions à ce projet sont bienvenues. Veuillez consulter CONTRIBUTING.md pour les directives sur comment contribuer au projet.

﻿# Licence : 
 Ce projet est distribué sous licence MIT. Voir le fichier LICENSE pour plus de détails.
