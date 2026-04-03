# 🎯 QUIZZEO

![Quizzeo Logo](public/assets/logo.png)

Une plateforme de quiz moderne et intuitive conçue pour les établissements scolaires et les entreprises.
IMPORTANT : Ce projet n'est pas à jour, les fonctionnalités decrite dans ce README ne sont pas toute implémentée.

## ✨ Fonctionnalités

### 🔐 Système d'Authentification
- Système multi-rôles (Écoles, Entreprises, Étudiants)
- Vérification CAPTCHA sécurisée
- Gestion de profil personnalisé

### 👥 Rôles Utilisateurs

#### 🛡️ Administrateur
- Tableau de bord complet de gestion des utilisateurs
- Supervision et modération des quiz
- Suivi en temps réel des activités utilisateurs

#### 🏫 Écoles
- Création de QCM personnalisés
- Suivi des performances des étudiants
- Gestion du cycle de vie des quiz

#### 💼 Entreprises
- Création de sondages et évaluations
- Questions QCM et questions ouvertes
- Outils d'analyse des réponses

#### 👤 Utilisateurs
- Système d'affiliation aux institutions
- Participation aux quiz
- Suivi des performances

## 🚀 Installation

### Prérequis
- PHP 7.4+
- Serveur web (Apache/Nginx)
- Navigateur web moderne

### Installation

1. Cloner le dépôt
```bash
https://github.com/NansPwlk/PROJET-WEB.git
```

2. Configurer les permissions des dossiers
```bash
chmod 755 data/
```

3. Configurer votre serveur web

4. Accéder à l'application via votre navigateur

## 📁 Structure du Projet
```
quizzeo/
├── 📂 data/               # Stockage des données
├── 📂 php/               # Logique backend
│   ├── admin/
│   ├── auth/
│   └── quiz/
└── 📂 public/            # Assets frontend
    ├── assets/
    ├── css/
    └── js/
```

## 🛠️ Technologies Utilisées
- PHP
- JavaScript
- HTML5
- CSS3

## 🔒 Sécurité
- Hashage des mots de passe avec Bcrypt
- Validation des entrées
- Protection CSRF
- Gestion sécurisée des sessions

## 🤝 Contribution
Les pull requests sont les bienvenues. Pour les changements majeurs, veuillez d'abord ouvrir une issue pour discuter des modifications souhaitées.

## 🚦 État du Développement
- ✅ Système d'Authentification
- ✅ Création de Quiz
- ✅ Tableau de Bord Utilisateur
- ✅ Panel Administrateur
- 🚧 Analyse des Réponses (En cours)

## 📝 Licence
[MIT](https://choosealicense.com/licenses/mit/)

## 👨‍💻 Auteur
**LEVY YANNIS**, 
**DUCRET ALEXANDRE**, 
**PAWLAK Nans**

## 🙏 Remerciements
- Tous les contributeurs qui ont aidé à façonner ce projet

---

