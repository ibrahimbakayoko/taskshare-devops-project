# 🚀 Taskshare – Projet DevOps Complet

Bienvenue dans le dépôt **central** du projet **Taskshare**.  
Ce dépôt sert de point d’entrée unique pour comprendre la vision globale, l’architecture et les composants du projet.  
Il contient la documentation complète ainsi que les liens vers les dépôts satellites.

---

## 📌 Présentation du projet

**Taskshare** est une application de gestion collaborative de tâches.  
L’objectif de ce projet est de mettre en place une infrastructure **DevOps moderne** pour :  

- Développer, conteneuriser et déployer l’application Taskshare.  
- Automatiser le provisionnement, la configuration et le déploiement.  
- Mettre en œuvre un pipeline **CI/CD complet** avec tests, qualité de code, build et déploiement automatique.  
- Surveiller et sécuriser l’ensemble de la plateforme en production.  

---

## 🏗️ Architecture globale

L’architecture s’appuie sur les piliers suivants :  

- **Terraform** : Provisionnement de l’infrastructure Cloud.  
- **Ansible** : Automatisation de la configuration et déploiement du cluster Kubernetes (K3s).  
- **Helm** : Packaging et déploiement applicatif.  
- **MariaDB Galera** : Base de données hautement disponible.  
- **Prometheus & Grafana** : Supervision et observabilité.  
- **CI/CD** : Pipelines d’intégration et déploiement continu.  

📌 Schéma d’architecture globale :  

- [Architecture](Docs/taskshare-infra.png)

---

## 📂 Dépôts satellites

🔹 **Infrastructure & Cloud**
- [Terraform – Provisionnement PROXMOX](https://github.com/ibrahimbakayoko/terrafom-taskshare.git)  
- [Ansible – Déploiement des services](https://github.com/ibrahimbakayoko/taskshare-ansible.git)  
- [Ansible – Déploiement de Taskshare](https://github.com/ibrahimbakayoko/taskshare-backend.git)  

🔹 **Application**
- [Backend Taskshare (Node.js)](https://github.com/ibrahimbakayoko/taskshare-backend.git)  
 
---

## 📖 Documentation complète

Le rapport détaillé du projet (contexte, conception, déploiement, CI/CD, monitoring, sécurité) est disponible dans :  

👉 [📘 docs/rapport.md](Docs/Rapport-TaskShare(2).pdf)  

---

## 👨‍💻 Auteur

Projet réalisé par **Brahima BAKAYOKO**, dans le cadre d’un projet DevOps intégrant :  
Terraform, Ansible, Kubernetes, Helm, Docker, Jenkins, Prometheus, Grafana et GitHub Actions.  

---
