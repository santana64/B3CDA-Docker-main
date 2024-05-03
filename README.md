Description du Projet
Ce projet, intitulé "B3CDA-Docker-main", met en œuvre Docker pour conteneuriser une application de gestion de produits. L'objectif est de fournir une infrastructure portable et reproductible pour le déploiement et le développement de l'application, tout en supportant différents moteurs de base de données.

Fonctionnalités
Conteneurisation avec Docker : Isolation complète de l'environnement pour éviter les conflits de dépendances.
Support multi-base de données : Compatible avec plusieurs systèmes de gestion de base de données pour une flexibilité maximale.
Déploiement facile et rapide : Démarrez votre environnement de développement en quelques commandes.
Prérequis
Docker
Docker Compose
Installation et Démarrage
Clonage du dépôt
Pour obtenir le projet, clonez le dépôt GitHub :

bash
Copy code
git clone https://github.com/santana64/B3CDA-Docker-main.git
cd B3CDA-Docker-main
Construction et Lancement des Conteneurs
Construisez les images Docker et lancez les conteneurs :

bash
Copy code
docker-compose up -d
Accès à l'Application
Une fois les conteneurs en fonction, accédez à l'application via : http://localhost:8080

Gestion de Version
Le projet utilise Git pour le contrôle de version. Les différentes configurations de base de données sont gérées dans des branches séparées pour une organisation claire du développement.

Branches Principales
Main : Contient la version de développement la plus récente avec PostgreSQL.
Version1 : Contient la première version de l'application utilisant MySQL 5.7.
Version2 : Branche pour les tests et mises à jour avec MySQL 8.3.
Workflow de Versionning
Pour contribuer au projet, veuillez créer une nouvelle branche à partir de la branche appropriée pour chaque nouvelle fonctionnalité ou correction. Après les tests, les modifications peuvent être fusionnées dans la branche cible.

Configuration
Dockerfile : Contient les directives pour construire l'image Docker de l'application PHP.
Dockerfile.postgresql : Spécifie les étapes pour construire l'image Docker pour PostgreSQL.
docker-compose.yml : Définit les services Docker pour l'application et la base de données.
Utilisation des Services de Base de Données
Vous pouvez utiliser le service PostgreSQL configuré pour gérer les données. Les détails de connexion sont spécifiés dans docker-compose.yml.

Contribution
Les contributions à ce projet sont bienvenues. Veuillez consulter CONTRIBUTING.md pour les directives sur comment contribuer au projet.

Licence
Ce projet est distribué sous licence MIT. Voir le fichier LICENSE pour plus de détails.

