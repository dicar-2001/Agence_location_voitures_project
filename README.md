🚗 Gestion d’Agence de Location de Véhicules
📌 Description

Ce projet est une application Python qui simule le fonctionnement d’une agence de location de véhicules.
Il permet de gérer un parc automobile, d’enregistrer des clients, de traiter les locations actives et de générer des contrats de location une fois les véhicules retournés.

Le système inclut également la sauvegarde des données (JSON) et la génération de rapports d’activité (revenus mensuels et utilisation de la flotte).

🎯 Objectif du projet

Automatiser la gestion d’une agence de location.

Permettre une meilleure organisation du parc automobile.

Suivre les contrats de location et calculer les coûts en temps réel.

Générer des statistiques et rapports pour l’analyse de performance.

⚙️ Fonctionnalités principales

✅ Gestion des véhicules : ajout, affichage, mise en maintenance, disponibilité.

✅ Gestion des clients : enregistrement, recherche et affichage.

✅ Gestion des locations : louer un véhicule, retourner un véhicule, créer un contrat.

✅ Historique des contrats : enregistrement des locations passées.

✅ Sauvegarde et chargement : persistance des données en JSON.

✅ Rapports et analyses : statistiques et graphiques avec pandas et matplotlib.

🏗️ Architecture du projet

Le projet est basé sur la Programmation Orientée Objet (POO).

📌 Diagramme UML


(Le diagramme ci-dessus illustre les classes principales et leurs relations)

📌 Classes principales

Vehicule (classe parent)

VoitureTourisme

Utilitaire

Client

LocationActive

ContratLocation

Agence (gestionnaire principal)

AgencePersistante (ajout persistance JSON)

🛠️ Technologies utilisées

Python 3.12+ → langage principal.

JSON → persistance des données.

Pandas → analyse et statistiques.

Matplotlib → visualisation des revenus.

Datetime → gestion des dates et durées.

POO (Programmation Orientée Objet) → structuration du projet.
