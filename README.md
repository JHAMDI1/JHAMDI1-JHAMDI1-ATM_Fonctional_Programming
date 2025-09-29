# ATM Functional Programming (C++)

Simulation d’un **Distributeur Automatique de Billets (DAB/ATM)** en C++, en appliquant les principes de la **programmation fonctionnelle**.

---

## 🎯 Objectif du projet

Ce programme console vise à simuler les opérations bancaires d’un automate de billets, tout en adoptant une approche fonctionnelle pour la structure du code.  
L’idée est de proposer un système simplifié, mais extensible, et d’expérimenter la gestion des comptes et transactions avec des fichiers texte comme stockage.

---

## 🛠 Fonctionnalités

- Authentification des utilisateurs (identifiant + mot de passe)  
- Consultation du solde  
- Dépôts et retraits  
- Historique des opérations  
- Gestion des comptes clients via fichier texte  
- Interface en console via menus interactifs  

---

## 🧩 Architecture & style de programmation

- Le code est organisé autour de **fonctions pures** pour les opérations principales (sans effet de bord si possible).  
- Utilisation de structures de données simples pour représenter les comptes et transactions.  
- Persistence des données via fichiers texte (`Clients.txt`, etc.).  
- Chaque module / fonction se concentre sur une responsabilité spécifique (séparation des préoccupations).  

---

## 📥 Installation & exécution

1. Clone le dépôt  
   ```bash
   git clone https://github.com/JHAMDI1/JHAMDI1-JHAMDI1-ATM_Fonctional_Programming.git
