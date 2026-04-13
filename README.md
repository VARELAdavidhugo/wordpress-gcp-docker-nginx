# 🚀 Déploiement d’un site WordPress sur GCP avec Docker et Nginx

## 📌 Présentation

Ce projet consiste à déployer une application WordPress conteneurisée sur une machine virtuelle Google Cloud Platform.

L’architecture repose sur Docker pour la gestion des services, Nginx comme reverse proxy et Let’s Encrypt pour la sécurisation HTTPS.

---

## 🛠️ Technologies utilisées

- Linux (Ubuntu)
- Google Cloud Platform (Compute Engine)
- Docker / Docker Compose
- Nginx
- WordPress
- MariaDB
- OVHcloud (DNS)
- Certbot / Let’s Encrypt

---

## 🧱 Architecture

Utilisateur → DNS → GCP (VM) → Nginx → WordPress → MariaDB → Volumes Docker

---

## 🎯 Objectifs

- Déployer une application web sur le cloud  
- Conteneuriser les services  
- Mettre en place un reverse proxy  
- Sécuriser les échanges en HTTPS  
- Assurer la persistance des données  

---

## ⚙️ Étapes principales

1. Création de la VM sur GCP  
2. Installation de Docker et Docker Compose  
3. Déploiement de WordPress et MariaDB  
4. Configuration de Nginx  
5. Mise en place du HTTPS avec Certbot  
6. Configuration DNS via OVHcloud  
7. Tests et validation  

---

## 💼 Compétences démontrées

- Administration Linux  
- Déploiement cloud (GCP)  
- Docker / Docker Compose  
- Reverse proxy avec Nginx  
- Sécurisation HTTPS  
- Gestion réseau (DNS, HTTP/HTTPS)  

---

## 📄 Documentation

Le rapport complet du projet est disponible dans le dossier `/docs`.

---

## 👤 Auteur

**David Hugo VARELA DURAN**  
Administrateur Systèmes & DevOps Junior
