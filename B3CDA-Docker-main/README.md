# Gestion des produits avec Docker

Ce projet utilise Docker pour conteneuriser une application de gestion de produits. L'objectif est de fournir une infrastructure portable et reproductible pour le déploiement et le développement de l'application, en utilisant différents moteurs de base de données.

## Conteneurisation de l'application

L'application est conteneurisée à l'aide de Docker et Docker Compose. Voici les étapes principales pour utiliser ce projet :

1. **Clonage du dépôt Git :**
   git clone https://github.com/LiamImamovic/B3CDA-Docker/
   cd gestion-produits

2. **Construction et lancement des conteneurs :**
   docker-compose up -d

3. **Accès à l'application :**
   Une fois les conteneurs démarrés, vous pouvez accéder à l'application via votre navigateur web en utilisant l'URL http://localhost:8080.

## Utilisation

- Assurez-vous que Docker et Docker Compose sont installés sur votre système.
- Clonez le dépôt Git et accédez au répertoire du projet.
- Utilisez la commande `docker-compose up -d` pour construire les images et démarrer les conteneurs.
- Accédez à l'application via votre navigateur web en utilisant l'URL http://localhost:8080.
- Vous pouvez utiliser le conteneur PostgreSQL pour stocker les données de l'application. Les informations de connexion sont fournies dans le fichier `docker-compose.yml`.

## Configuration

- Le fichier `Dockerfile` contient les instructions pour construire l'image Docker de l'application PHP.
- Le fichier `Dockerfile.postgresql` contient les instructions pour construire l'image Docker de PostgreSQL.
- Le fichier `docker-compose.yml` définit les services Docker utilisés pour exécuter l'application et la base de données.
