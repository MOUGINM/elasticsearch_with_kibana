# Projet de Gestion de Données Elasticsearch 

## Description

Ce projet déploie une stack complète Elastic (Elasticsearch, Logstash, Kibana) via `docker-compose`. Il permet la gestion de données géospatiales, leur visualisation et leur traitement dans Kibana avec une base de données Elasticsearch. Des scripts Python sont inclus pour interagir avec Elasticsearch, manipuler les données et automatiser certaines tâches.

## Fonctionnalités

- **Elasticsearch** : Stockage et recherche de données.
- **Kibana** : Visualisation et dashboards analytiques.
- **Logstash** : Ingestion et transformation des données avant leur stockage dans Elasticsearch.
- **Support Géospatiale** : Gestion des coordonnées géographiques.
- **Scripts Python** : Automatisation, vérification des données et conversion CSV vers JSON.
- **Docker Compose** : Orchestration des containers Elasticsearch, Kibana, et Logstash.

## Pré-requis

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Python 3.x](https://www.python.org/downloads/)

## Installation

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/MOUGINM/elasticsearch_with_kibana/tree/main
   cd elasticsearch_with_kibana

2. Lancez la stack Elastic avec Docker Compose :
   ( Docker desktop doit être lancé )

   ```bash
   docker-compose up -d

4. Accédez à Kibana via  :

   ```bash
   http://localhost:5601






   
