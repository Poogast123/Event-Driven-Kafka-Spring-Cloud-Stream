# Activité Pratique N°1 – Event Driven Architecture avec Apache Kafka

Cette activité pratique consiste à mettre en place une **architecture orientée événements (Event Driven Architecture)** à l’aide de **Kafka** et **Spring Cloud Streams**.  
L’objectif est de comprendre le fonctionnement de Kafka, de configurer un environnement Dockerisé, et de développer une série de microservices capables de produire, consommer et analyser des flux de données en temps réel.

Le travail comprend plusieurs étapes :  
1. Mise en place de **Kafka via Docker** et test des échanges avec **Kafka-console-producer** et **Kafka-console-consumer**.  
2. Création d’applications **Spring Boot** intégrant **Kafka** et **Spring Cloud Streams** :  
   - Un **service Producer** exposant un contrôleur REST pour envoyer des messages.  
   - Un **service Consumer** pour lire et traiter les événements.  
   - Un **service Supplier** pour générer des événements périodiques.  
   - Un **service d’analyse en temps réel (Kafka Streams)** pour effectuer du traitement de flux et de l’agrégation de données.  
   - Une **application web** permettant de visualiser en temps réel les résultats des analyses.

Cette activité permet de maîtriser les concepts clés de l’**Event Driven Architecture**, du **traitement de flux de données**, et de l’intégration de **Kafka** dans un écosystème **Spring Cloud** moderne.
