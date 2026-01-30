🚀 Infrastructure Cloud de Supervision Centralisée – Zabbix & AWS
📌 Présentation

Ce projet consiste en la mise en place d’une infrastructure de supervision centralisée sur Amazon Web Services (AWS), basée sur Zabbix et déployée via Docker Compose.
L’objectif est de superviser un parc informatique hybride (Linux et Windows) à partir d’une plateforme unique, sécurisée et évolutive.

🎯 Objectifs

Déployer une architecture Cloud sécurisée sur AWS

Mettre en place un serveur Zabbix conteneurisé

Superviser des hôtes Linux et Windows

Visualiser les métriques systèmes en temps réel (CPU, RAM, disque, disponibilité)

🧰 Technologies utilisées

AWS (EC2, VPC, Security Groups)

Docker & Docker Compose

Zabbix

Ubuntu 22.04 / Windows Server

Git & GitHub

🏗️ Architecture

VPC avec sous-réseau dédié

Instances EC2 :

Serveur Zabbix (Ubuntu)

Client Linux

Client Windows

Zabbix Server, Web UI et base de données déployés en conteneurs

Agents Zabbix installés sur les hôtes clients



📊 Supervision

Collecte des métriques systèmes (CPU, mémoire, disque)

Tableaux de bord Zabbix personnalisés

Détection proactive des incidents via triggers

👤 Auteur & Encadrement

Auteur : NAFID WASSIM
Encadrant : Prof. Azzedine Khiat
