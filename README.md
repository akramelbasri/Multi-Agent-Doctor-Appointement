# Multi-Agent Doctor Appointment

Ce projet est une application de prise de rendez-vous médicaux basée sur une architecture multi-agents. Elle permet d’analyser les symptômes des patients, de rechercher des médecins appropriés, de gérer les rendez-vous et d’envoyer des notifications, le tout de manière automatisée grâce à l’intelligence artificielle.

## Fonctionnalités principales

Analyse des symptômes : Un agent dédié analyse les symptômes décrits par le patient.
Recherche de médecins : Un agent recherche les médecins disponibles correspondant aux besoins du patient.
Prise de rendez-vous : Un agent gère la réservation des créneaux de rendez-vous.
Notifications : Un service envoie des notifications par email pour confirmer les rendez-vous.
Gestion des conversations : Historique des échanges et recommandations personnalisées.

## Structure du projet

doctor-appointments/


├── agents/                # Agents intelligents (symptômes, recherche, réservation, workflow)

├── config/                # Configuration des modèles LLM et prompts

├── conversation/          # Historique des conversations

├── database/              # Données des rendez-vous, patients, médecins, etc.

├── llm/                   # Intégration et sélection des modèles de langage

├── services/              # Services métiers (prise de rendez-vous, notifications)

├── tests/                 # Tests unitaires

├── utils/                 # Utilitaires (envoi d'emails, formatage)

├── main.py                # Point d’entrée principal de l’application

├── README.md              # Ce fichier

└── pyproject.toml         # Dépendances et configuration du projet

## Installation
1. Cloner le dépôt :
   git clone https://github.com/votre-utilisateur/Multi-Agent-Doctor-Appointement.git
   cd Multi-Agent-Doctor-Appointement/doctor-appointments

2. Installer les dépendances
   pip install poetry
   poetry install

3. Configurer les fichiers nécessaires :
Adapter les fichiers de configuration dans config/ si besoin.

## Utilisation
Lancer l’application principale : poetry run python main.py

Technologies utilisées
- Python 3
- Poetry pour la gestion des dépendances
- Modèles LLM (Large Language Models)
- Architecture multi-agents

  

   
