# gestion_parc_informatique_epi_vehicule
Plateforme de gestion centralisée pour le parc IT, les EPI et les véhicules. Elle assure le suivi complet (CRUD), les affectations, les stocks et la cartographie réseau. Inclus : rapports de consommation des EPI et maintenance préventive de la flotte avec prédiction intelligente des prochaines vidanges.
1. Gestion du Parc Informatique & Réseaux

Ce module vise à assurer la disponibilité et la performance des outils de travail numériques.

    Inventaire Complet (CRUD) : Gestion du cycle de vie du matériel (ordinateurs, serveurs, tablettes) et des consommables (toners, câbles).

    Gestion des Affectations : Suivi précis du matériel prêté aux collaborateurs avec historique des mouvements.

    Cartographie Réseau : Visualisation dynamique de l'infrastructure (switchs, routeurs, points d'accès) pour faciliter le diagnostic en cas de panne.

    Flux de Demandes : Système de tickets pour la commande de consommables avec validation hiérarchique.

2. Gestion des EPI (Équipements de Protection Individuelle)

Un module critique pour la sécurité au travail et la conformité réglementaire.

    Suivi des Stocks : Gestion rigoureuse des casques, gants, chaussures de sécurité et vêtements haute visibilité.

    Attribution & Traçabilité : Enregistrement des dotations par employé pour garantir que chaque agent dispose des protections nécessaires.

    Analytique & Reporting : Génération de rapports automatiques sur la consommation des EPI, permettant d'identifier les besoins futurs et d'optimiser les budgets d'achat.

3. Gestion du Parc Automobile & Maintenance

Optimisation de la flotte de véhicules pour réduire les coûts d'exploitation et les temps d'immobilisation.

    Fiches Véhicules : Centralisation des données techniques, administratives (assurances, cartes grises) et état général.

    Gestion des Entretiens : Suivi des réparations, des révisions et des interventions mécaniques subies.

    Maintenance Prédictive : Algorithme de prédiction des dates de prochaines vidanges et révisions basé sur le kilométrage moyen et les fréquences d'utilisation, évitant ainsi l'usure prématurée des moteurs.

4. Objectifs et Valeur Ajoutée

    Centralisation : Une seule interface pour trois domaines logistiques majeurs, éliminant les fichiers Excel éparpillés.

    Optimisation des Coûts : Réduction du gaspillage des consommables et des EPI grâce à un suivi strict des sorties de stock.

    Proactivité : Passage d'une maintenance curative (réparer quand ça casse) à une maintenance préventive et prédictive
   (anticiper pour durer).
    Aide à la Décision : Les tableaux de bord offrent une visibilité en temps réel sur l'état global des ressources de Neemba.
   # Pour lancer le proejet
   1) Lancer Votre server web apache par exemple
   2) mettez le projet dans httdocs ou wwan si vous utilisez lampp
   3) importer la base de donnée dans SQL SERVER
   4) dans votre navigateur tapez : https:localhost/gestion_parc/frontend/views/connexion.php
      la redirection se fait en fonction du role
  1 ) Admin
      username: nalokoyo , password:nalo1234
   2) gestionnaire EPI
      username:issoufou.m password:MotDePasse1
    3) gestionnaire Parc informatique
      username:amadou.m password:MotDePasse2
  4) gestionnaire Vehicule
     username: 
