🏎️ F1Mates
**F1Mates** is a mobile application for betting with friends on Formula 1 races, without financial stakes.

📌 Main Features
* 📅 Grand Prix selection and tracking
* 🏆 Creation of rankings and predictions
* 📊 Advanced statistics and AI analysis
* 🏁 Group ("stable") creation for community play
* 👥 Profile management and friend interactions

🛠️ Technical Stack
* **Frontend**: React Native (Expo)
* **Backend**: Python (FastAPI/Flask)
* **Database**: Supabase (PostgreSQL)
* **AI & Statistics**: PyTorch / TensorFlow
* **Notifications**: Firebase Cloud Messaging

🚀 Installation
1. Clone the repo:

```sh
git clone https://github.com/user/f1mates.git
cd f1mates
```

2. Install dependencies:

```sh
npm install
```

3. Launch the application:

```sh
expo start
```

📄 License
Open-source project under MIT license.

# EN
# Quality Plan - F1Mates

## 1. Objectives

F1Mates is a friendly F1 betting application without financial stakes. The application allows users to predict Grand Prix results and compete with friends through rankings and statistics.

The goal of the quality plan is to define common rules, the development process, validation mechanisms, and deliveries to ensure a high-performance, reliable, and maintainable product.

## 2. Quality Plan

### 2.1 Team Activities

- **Design and development** of the mobile application
- **Database implementation** to store race and user information
- **Setup** of a discussion and ranking system
- **Testing and validation** of features
- **Continuous maintenance and improvements**

### 2.2 Standards and Best Practices

- Use of **Git and GitHub** for versioning and collaboration
- **AI utilization** for statistical analysis
- **Compliance with UX/UI best practices** for optimal user experience

### 2.3 Roles and Responsibilities

- **Product Owner**: Defines needs and priorities
- **Developers**: Implement features
- **UX/UI Designer**: Designs the interface
- **Testers**: Ensure product quality

## 3. Development Process

### 3.1 Tools Used

- **Code management**: GitHub
- **Configuration and deployment**: CI/CD via GitHub Actions
- **Project management**: Trello
- **Frameworks**: 
  - React Native / Expo for mobile application
  - Python with Flask or FastAPI for APIs
- **Database**: Supabase (PostgreSQL)
- **AI and statistics**: Python with PyTorch/TensorFlow
- **Notifications**: Firebase Cloud Messaging

### 3.2 Development Flow

1. Sprint planning and user story definition
2. Feature development with unit tests
3. Code review and validation
4. Functional testing and corrections
5. Production deployment and performance monitoring

## 4. Functional Requirements

### 4.1 PBS (Product Breakdown Structure)

#### 1. Mobile Application
- User interface (UI)
- Interaction management

#### 2. Backend
- User management API
- Race management API
- Betting management API

#### 3. Database
- User storage
- Race result storage
- Betting and ranking storage

#### 4. AI & Statistics System
- Driver performance analysis
- Predictions based on race history
- Recommendation generation

### 4.2 Screens and Features

#### HomeScreen
- Grand Prix selection
- GP stage selection
- List of conversations with friends

#### ClassementScreen
- Driver ranking organization for a GP
- Drag & drop to rearrange ranking

#### RaceInfoScreen
- Race details: track, country, location, date, length, number of laps
- Race history and records

#### AddGroupScreen
- Team (stable) creation
- Choice of emblem, name, description
- Permission management (open or invitation-only group)

#### ClassementScreen (Global)
- Podium display with top 3
- Ranked player list

#### StatistiquesScreen
- Advanced race and driver analysis
- AI-based predictions (using PyTorch/TensorFlow)

#### UserScreen
- Profile management: photo, nickname, abbreviation (3 letters)
- Access to friends, settings, notifications, help, and logout

## 5. Validation Criteria (Definition of Done)

- Feature developed and integrated
- Unit and functional tests passed successfully
- Code review completed and approved
- Documentation updated
- Pre-production environment deployment validated

## 6. Delivery Management

- Build versioning (e.g., v1.0.0)
- Documentation associated with each release
- Tests performed before publication
- Gradual deployment via Firebase App Distribution

**This quality plan ensures a structured and effective development for F1Mates!**


# FR
# Plan de Qualité - F1Mates

## 1. Objectifs

F1Mates est une application de paris amicaux sur les courses de F1, sans enjeu financier. L'application permet aux utilisateurs de prédire les résultats des Grands Prix et de concourir avec leurs amis via des classements et des statistiques.

L'objectif du plan de qualité est de définir les règles communes, le processus de développement, les mécanismes de validation et les livraisons afin de garantir un produit performant, fiable et maintenable.

## 2. Plan de Qualité

### 2.1 Activités de l'équipe

- **Conception et développement** de l'application mobile
- **Implémentation d'une base de données** pour stocker les informations des courses et des utilisateurs
- **Mise en place** d'un système de discussion et de classement
- **Tests et validation** des fonctionnalités
- **Maintenance et améliorations** continues

### 2.2 Normes et Bonnes Pratiques

- Utilisation de **Git et GitHub** pour le versioning et la collaboration
- Utilisation de **l'IA pour l'analyse des statistiques**
- **Conformité aux bonnes pratiques UX/UI** pour une expérience utilisateur optimale

### 2.3 Rôles et Responsabilités

- **Product Owner** : Définit les besoins et priorités
- **Développeurs** : Implémentent les fonctionnalités
- **Designer UX/UI** : Conçoit l'interface
- **Testeurs** : Assurent la qualité du produit

## 3. Processus de Développement

### 3.1 Outils Utilisés

- **Gestion de code** : GitHub
- **Configuration et déploiement** : CI/CD via GitHub Actions
- **Gestion de projet** : Trello
- **Frameworks** : 
  - React Native / Expo pour l'application mobile
  - Python avec Flask ou FastAPI pour les APIs
- **Base de données** : Supabase (PostgreSQL)
- **IA et statistiques** : Python avec PyTorch/TensorFlow
- **Notifications** : Firebase Cloud Messaging

### 3.2 Déroulement du Développement

1. Sprint planning et définition des user stories
2. Développement des fonctionnalités avec tests unitaires
3. Code review et validation
4. Tests fonctionnels et correctifs
5. Mise en production et suivi des performances

## 4. Exigences Fonctionnelles

### 4.1 PBS (Product Breakdown Structure)

#### 1. Application Mobile
- Interfaces utilisateur (UI)
- Gestion des interactions

#### 2. Backend
- API de gestion des utilisateurs
- API de gestion des courses
- API de gestion des paris

#### 3. Base de données
- Stockage des utilisateurs
- Stockage des résultats de courses
- Stockage des paris et classements

#### 4. Système IA & Statistiques
- Analyse des performances des pilotes
- Prédictions basées sur l'historique des courses
- Génération de recommandations

### 4.2 Écrans et Fonctionnalités

#### HomeScreen
- Sélection du Grand Prix
- Sélection des étapes du GP
- Liste des conversations avec les amis

#### ClassementScreen
- Organisation du classement des pilotes pour un GP
- Drag & drop pour réorganiser le classement

#### RaceInfoScreen
- Détails de la course : tracé, pays, lieu, date, longueur, nombre de tours
- Historique et records de la course

#### AddGroupScreen
- Création d'un groupe (écurie)
- Choix d'un écusson, nom, description
- Gestion des permissions (groupe ouvert ou sur invitation)

#### ClassementScreen (Global)
- Affichage du podium avec les 3 premiers
- Liste classée des joueurs

#### StatistiquesScreen
- Analyse avancée des courses et pilotes
- Prédictions basées sur l'IA (utilisant PyTorch/TensorFlow)

#### UserScreen
- Gestion du profil : photo, pseudo, abbréviation (3 lettres)
- Accès aux amis, paramètres, notifications, aide et déconnexion

## 5. Critères de Validation (Definition of Done)

- Fonctionnalité développée et intégrée
- Tests unitaires et fonctionnels passés avec succès
- Revue de code effectuée et approuvée
- Documentation mise à jour
- Déploiement en environnement de préproduction validé

## 6. Gestion des Livraisons

- Versionnage des builds (ex : v1.0.0)
- Documentation associée à chaque release
- Tests réalisés avant publication
- Déploiement progressif via Firebase App Distribution

**Ce plan de qualité garantit un développement structurant et efficace pour F1Mates !**
