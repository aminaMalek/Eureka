# Eureka — Moteur de recherche d'articles scientifiques

Eureka est un site web conçu pour faciliter la recherche d’articles scientifiques. Le projet s'appuie sur Elasticsearch pour permettre l’indexation rapide et efficace d’un grand volume de documents. L’ensemble du système est conteneurisé à l’aide de Docker, ce qui simplifie le déploiement et garantit la portabilité.

## Fonctionnalités

- Moteur de recherche rapide basé sur Elasticsearch
- Indexation d’articles scientifiques volumineux
- Interface web simple et intuitive
- Déploiement via Docker et Docker Compose

## Technologies utilisées

- Backend : Django
- Frontend : React Js
- Moteur de recherche : Elasticsearch
- Conteneurisation : Docker
- Base de données : Postgesql

## Installation et exécution

1. Cloner le dépôt du projet :
git clone https://github.com/aminaMalek/Eureka.git
cd aureka

2. Lancer les conteneurs Docker :
docker-compose up --build
