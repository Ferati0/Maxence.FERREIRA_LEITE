====================================================================

FERREIRA LEITE Maxence -Portfolio Informatique – Cybersécurité

====================================================================

## PROFIL
------

Étudiant en 3ème année de Bachelor Cybersécurité à Ynov Campus Sophia Antipolis pour l'année 2026/2027, je construis progressivement un profil orienté sécurité des systèmes, administration réseaux et développement d’outils techniques.

Mon parcours associe une base universitaire en Licence Sciences et Technologies avec une spécialisation en informatique et intelligence artificielle, puis une orientation professionnelle vers la cybersécurité. 

Je développe mes compétences à travers :
  - des projets académiques en programmation et systèmes
  - des exercices pratiques en environnement Linux
  - la progression sur des plateformes de cybersécurité comme TryHackMe

Sérieux, discipliné et curieux, je recherche une alternance me permettant de rejoindre une équipe technique, de monter en compétences et de contribuer à des missions concrètes en cybersécurité, systèmes ou réseaux.

À moyen et long terme, mon objectif est de poursuivre une trajectoire cohérente vers un Mastère expert en cybersécurité à Ynov campus, avec une ambition académique clairement définie : préparer un dossier solide pour une candidature en Master 2 Informatique Réseaux, parcours UBiNet, à l’Université Côte d’Azur. Mon parcours vise à avoir des compétences solides à la fois professionnel et théorique.

Rythme recherché :
  - 1 semaine en formation
  - 2 semaines en entreprise


## COMPETENCES TECHNIQUES
----------------------

Programmation :
  - Python
  - C
  - Java
  - R
  - SQL
  - JavaScript
  - HTML / CSS

Compétences associées :
  - structuration modulaire de programmes
  - algorithmique
  - scripting
  - logique de développement orientée outils techniques

Systèmes :
  - Linux
  - Windows
  - utilisation de la ligne de commande
  - gestion des fichiers et permissions
  - notions de virtualisation et d’environnements de test (utilisation de UTM)

Réseaux :
  - bases TCP/IP
  - adressage IP
  - communication client / serveur
  - principes de fonctionnement réseau

Outils / environnements :
  - terminal Linux
  - Python pour scripting
  - R / R Shiny
  - plateformes d’apprentissage cybersécurité (tryhackme)

## PROJETS REALISES
----------------

Projet 1 : Manipulation de polynômes en R (2023) [voir le projet]

Contexte :
  Réalisation d’un module en langage R permettant de représenter, manipuler et exploiter mathématiquement des polynômes à partir d’une représentation dense par vecteur.

Description détaillée :
  Ce projet a consisté à concevoir une base logicielle capable de modéliser des polynômes puis d’implémenter différentes opérations classiques associées à ces objets         mathématiques. L’objectif n’était pas seulement de produire un résultat correct, mais aussi de proposer une structure claire, réutilisable et cohérente du point de vue     algorithmique.

Objectifs :
  - représenter proprement un polynôme sous forme vectorielle
  - implémenter les opérations algébriques de base
  - proposer une évaluation numérique selon plusieurs approches
  - visualiser graphiquement les résultats pour interprétation

Fonctionnalités développées :
  - addition et manipulation de polynômes
  - évaluation numérique par méthode naïve
  - évaluation optimisée par méthode de Horner
  - calcul et visualisation du polynôme
  - visualisation de la dérivée
  - visualisation de la primitive

Apports techniques :
  - travail sur la logique algorithmique
  - structuration d’un programme scientifique
  - réflexion sur la performance d’implémentation
  - comparaison entre différentes méthodes de calcul

Compétences développées :
  - algorithmique
  - calcul scientifique
  - modularisation
  - analyse de complexité
  - représentation de données mathématiques


Projet 2 : Convertisseur de bases et système bibi-binaire en R (2023) [voir le projet](https://github.com/Ferati0/projet-R_ShinyBinare)

Contexte :
  Développement d’une application en R permettant de convertir des entiers entre plusieurs systèmes de numération, avec une interface interactive réalisée à l’aide du        framework Shiny.

Description détaillée :
  L’objectif de ce projet était de concevoir une application pédagogique et fonctionnelle capable de gérer des conversions depuis et vers différentes bases numériques,       tout en proposant une interface utilisable et structurée. Le projet incluait également l’implémentation d’un système d’écriture bibi-binaire reposant sur un regroupement   binaire par blocs de 4 bits.

Objectifs :
  - convertir un entier écrit dans une base quelconque vers la base décimale
  - convertir un entier décimal vers une base cible
  - gérer les bases de 2 à 36
  - intégrer une interface simple et interactive
  - implémenter le système bibi-binaire

Fonctionnalités développées :
  - conversion base quelconque vers décimal
  - conversion décimal vers base cible
  - validation des caractères autorisés selon la base choisie
  - logique de conversion adaptée au système bibi-binaire

Apports techniques :
  - mise en œuvre d’algorithmes de conversion
  - gestion des cas limites et contrôle des entrées
  - séparation entre logique métier et interface utilisateur

Compétences développées :
  - algorithmique
  - manipulation de chaînes de caractères
  - logique de représentation de l’information


Projet 3 : Mini rsync – Projet système Linux (2023, modifié en 2024, projet de groupe) [voir le projet](https://github.com/Ferati0/mini-rsync)

Contexte :
  Développement d’une version simplifiée de l’outil Unix rsync en Python afin de comprendre concrètement les mécanismes de synchronisation de fichiers, la logique d’échange entre processus et la communication client / serveur.

Description détaillée :
  Ce projet est l’un des plus significatifs de mon parcours car il combine systèmes, réseau et programmation. Le programme permet de synchroniser des fichiers entre deux     répertoires, en local ou via le réseau, à l’aide d’un transfert incrémental par blocs. Le fonctionnement repose sur une architecture séparant plusieurs rôles, notamment    l’émetteur, le générateur et le récepteur, avec utilisation de mécanismes systèmes tels que les pipes, les sockets TCP et SSH.

L’objectif principal était de reproduire de manière simplifiée la logique d’un outil réel de synchronisation, tout en approfondissant la compréhension de la gestion des fichiers, des communications réseau et des mécanismes d’échange entre composants logiciels.

Objectifs :
  - comprendre les principes de synchronisation de fichiers
  - manipuler le système de fichiers sous Linux
  - mettre en œuvre une logique client / serveur
  - explorer les mécanismes systèmes utiles à la transmission de données
  - développer un outil inspiré d’un cas réel

Fonctionnalités développées :
  - copie récursive de répertoires
  - comparaison de fichiers
  - détection de différences entre source et destination
  - mise à jour automatique des éléments modifiés
  - synchronisation locale et réseau
  - transfert incrémental par blocs
  - communication via sockets TCP
  - utilisation de SSH selon le scénario
  - utilisation de pipes dans l’architecture globale

Architecture et logique technique :
  - séparation fonctionnelle des rôles
  - traitement orienté synchronisation
  - échanges entre composants
  - logique de comparaison avant transfert
  - compréhension du compromis entre simplicité, performance et fiabilité

Apports techniques :
  - approfondissement du fonctionnement Linux
  - meilleure compréhension des mécanismes bas niveau utiles en système
  - mise en pratique de concepts réseaux
  - approche concrète de la synchronisation distribuée
  - travail sur une problématique proche d’un usage professionnel

Compétences développées :
  - Python
  - programmation système
  - gestion du système de fichiers
  - architecture client / serveur
  - sockets TCP
  - SSH
  - logique de synchronisation
  - structuration d’un projet technique plus complet

## EXPERIENCE PROFESSIONNELLE
---------------------------

Manœuvre en bâtiment – JLF Renov (CDD)
Été 2016 à mars 2025

Missions :
  - interventions sur différents chantiers
  - participation à des travaux variés : plaquiste, maçonnerie, carrelage, couverture, peinture
  - accompagnement et formation de nouvelles recrues

Apports :
  - sens du travail en équipe
  - adaptation rapide à différents contextes
  - capacité à transmettre des consignes techniques


Équipier polyvalent – Burger King (CDI)
Juillet 2023 à mai 2024

Missions :
  - gestion des commandes
  - maintien d’un service client de qualité
  - formation des nouvelles recrues

Apports :
  - efficacité en situation de pression
  - réactivité
  - organisation
    

Juge-arbitre de tennis – All In Tennis Academy
2022 à 2024

Missions :
  - planification et gestion logistique de compétitions
  - gestion des plannings
  - médiation en cas de litiges ou tensions

Apports :
  - sens de l’organisation
  - gestion de situations conflictuelles
  - prise de décision

Éducateur tennis – All In Tennis Academy (Stage)
2022 à 2023

Missions :
  - encadrement de groupes d’adultes et d’enfants
  - suivi des séances
  - accompagnement hors compétition

Apports :
  - pédagogie
  - communication
  - capacité d’encadrement
  - adaptation à différents profils


## FORMATION
----------

Bachelor Cybersécurité – Ynov Campus Sophia Antipolis (2026 – 2027)

Orientation :
  - cybersécurité
  - systèmes
  - réseaux

Objectif de cette étape :
  - consolider les bases techniques en sécurité informatique
  - documenter des projets concrets
  - développer un profil cohérent pour l’alternance
  - renforcer la crédibilité d’un parcours orienté sécurité des infrastructures


Licence Sciences et Technologies – option Informatique / Intelligence Artificielle
2022 – 2025

Éléments marquants :
  - acquisition de bases solides en informatique
  - travail sur des projets de programmation
  - développement de la logique algorithmique
  - approche universitaire structurée
  - spécialisation progressive vers les sujets informatiques et IA

Diplôme obtenu :
  - DEUG Sciences et Technologies (2024)


Double licence Mathématiques & Informatique
2021 – 2022

Apports :
  - consolidation des bases scientifiques
  - développement de la rigueur
  - renforcement des capacités d’analyse
  - base utile pour la logique, l’algorithmique et la résolution de problèmes


Formation militaire – École Nationale des Sous-Officiers d’Active
Spécialité SIC Informatique
2025

Apports :
  - culture de la discipline
  - rigueur
  - capacité d’adaptation
  - capacités à commander


Certifications / formation complémentaire / progression visée
  - pratique sur TryHackMe
  - montée en compétence progressive en réseaux et sécurité
  - intérêt pour des formations complémentaires de type réseaux / cybersécurité
  - volonté de renforcer le profil par des projets documentés, des labs et des apprentissages parallèles (passer les certifiactions comme le ccna ou compTIA secure+ pendant l'année 2026/2027)


Projection académique à moyen et long terme
  - poursuite vers un Mastère expert cybersécurité
  - développement d’un profil technique et académique cohérent
  - préparation d’un dossier solide pour une candidature en Master 2 Informatique
  - objectif visé : Master 2 Informatique Réseaux, parcours UBiNet, Université Côte d’Azur


## SOFT SKILLS
------------

  - Discipline
  - Organisation
  - Persévérance
  - Esprit d’équipe
  - Capacité d’apprentissage
  - Sens des responsabilités

Ces qualités ont été développées à travers mes études, mes projets techniques, mes expériences professionnelles et mon engagement dans des activités sportives et d’encadrement.

## CENTRES D’INTERET
------------------

  - Informatique
  - Cybersécurité
  - Tennis
  - Musculation
  - Voyages en France et en Europe

Le sport occupe une place importante dans mon parcours personnel. Il m’a permis de développer discipline, régularité, esprit de compétition et sens de l’engagement, des qualités que je transpose aujourd’hui dans mes études et mes projets techniques.


## CONTACT
-------

Nom        : FERREIRA LEITE Maxence
Email      : maxence.ferreiraleite@hotmail.com
Téléphone  : 06 19 20 46 67
LinkedIn   : www.linkedin.com/in/maxence-ferreira-leite
GitHub     :

Informations complémentaires :
  - Permis B
  - Véhiculé
