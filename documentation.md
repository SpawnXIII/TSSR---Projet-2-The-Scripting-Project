# TSSR - Projet 2 : The Scripting Project

## Sommaire
1. Objectifs du Projet
2. Éléments à Implémenter
3. Livrables
4. Avancement et Présentation
5. Groupes et Rôles

---

## 1. Objectifs du Projet

### But de la Formation
- **Architecture Client/Serveur** : Mise en place d'une architecture complète.
- **Scripts Bash et PowerShell** : Création et gestion de scripts pour automatiser les tâches sur différents systèmes.
- **Travail en Équipe** : Réalisation du projet en collaboration.
- **Documentation** : Consignation de chaque étape du processus.
- **Démonstration Finale** : Présentation des résultats finaux.

### Objectifs du Projet
- **Objectif Principal** : 
  - Exécution d’un script PowerShell depuis un serveur Windows pour cibler des machines Windows.
  - Exécution d’un script Bash depuis un serveur Debian pour cibler des machines Ubuntu.

- **Objectif Secondaire (Optionnel)** :
  - Interagir avec des machines clientes utilisant différents systèmes d'exploitation pour une évaluation bonifiée.

---

## 2. Éléments à Implémenter

### Clients
- **Client Windows 10**
  - Nom : `CLIWIN01`
  - Utilisateur : `wilder` (admin local)
  - IP : `172.16.10.20/24`

- **Client Ubuntu 22.04/24.04 LTS**
  - Nom : `CLILIN01`
  - Utilisateur : `wilder` (sudo)
  - IP : `172.16.10.30/24`

### Serveurs
- **Serveur Windows Server 2022**
  - Nom : `SRVWIN01`
  - Compte Admin : `Administrator`
  - IP : `172.16.10.5/24`

- **Serveur Debian 12**
  - Nom : `SRVLX01`
  - Compte : `root`
  - IP : `172.16.10.10/24`

### Scripts
- **PowerShell Script (.ps1)**
  - S'exécute sur Windows Server 2022 avec PowerShell Core (v7.4 ou plus).
  - Peut nécessiter plusieurs dépendances de fichiers.
  
- **Bash Script (.sh)**
  - S'exécute sur Debian 12.
  - Utilise les commandes shell et peut inclure plusieurs dépendances.

---

## 3. Livrables

### À soumettre
- **Scripts** : 
  - Un script PowerShell
  - Un script Bash
- **Dépôt Git/GitHub** : Un dépôt Git par groupe nommé sous la forme `TSSR-2409-P2-Gx`.
- **Documentation** :
  - README.md
  - INSTALL.md
  - USER_GUIDE.md

---

## 4. Avancement et Présentation

### Exemple d'Avancement par Semaine
1. **Semaine 5**
   - **Lundi** : Analyse des besoins et mise en place des objectifs de sprint.
   - **Mardi - Vendredi** : Installation, configuration, développement du squelette des scripts, et premières présentations.

2. **Semaine 6-8**
   - Avancement du codage, debug, test, et mises à jour de la documentation.

### Présentation des Projets
- Présentations hebdomadaires de 5 à 10 minutes par groupe.
- Démonstration finale de 10 à 15 minutes, couvrant la totalité des fonctionnalités implémentées.

---

## 5. Groupes et Rôles

### Rôles Importants
- **Scrum Master (SM)** : Responsable de l'application de la méthode Scrum et de la communication.
- **Product Owner (PO)** : Garant de la qualité et représentant des besoins du client.

### Attribution des Rôles
- Les rôles tournent chaque sprint pour une meilleure répartition des responsabilités.
  
---

## Documentation Complémentaire

### Documentation Générale
- **Contexte et Objectifs** : Présentation du projet et des objectifs finaux.
- **Membres et Rôles** : Détails sur chaque membre et leur rôle respectif par sprint.
- **Choix Techniques** : Description des OS, versions, etc.
- **Difficultés et Solutions** : Problèmes rencontrés et solutions mises en œuvre.
- **Améliorations Futures** : Suggestions d’améliorations possibles pour les versions futures.

### Documentation pour l’Administrateur
- **Prérequis Techniques**
- **Étapes d’Installation et Configuration**
- **FAQ** : Solutions aux problèmes connus.

### Documentation Utilisateur
- **Utilisation de Base et Avancée**
- **FAQ Utilisateur**

---

## Journalisation des Activités

- **Fichier Journal (`log_evt.log`)**
  - Stocke les activités sous forme `<Date>-<Heure>-<Utilisateur>-<Événement>`.
  - Début et fin du script marqués par `********StartScript********` et `*********EndScript********`.
  - Localisation : 
    - Windows : `C:\Windows\System32\LogFiles`
    - Linux : `/var/log`

---
