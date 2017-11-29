# Examen de certification CERT04.1: Concevoir une base de données

Cet examen est  nécessaire à l'évaluation de votre aptitude à passer la certification et ses résultats sont demandés par l'institution l'organisant.

Le but de cet examen est de vous faire répondre à un cahier des charges quant à la création d'une BDD pour une application web.

Pour cet exercice, l'application en question servira à la gestion du planning des concerts des Trans'musicales .

Cet examen est à faire en deux étapes, une première modélisation entité/association puis la modélisation physique des données.

## Temps imparti
Vous avez 3 heures pour réaliser cette évaluation.

## Contexte

Le festival a des soucis dernièrement avec son logiciel pour la gestion des concerts et a fait appel à vous. Ils aimeraient que vous fassiez un prototype pour un outil le remplaçant.


Une analyse a été réalisée par votre chef de projet et il a morcelé le tout en plusieurs sprints.

Dans un premier temps, l'application devra juste pouvoir permettre la saisie des groupes.
Et il vous demande d'en réaliser la modélisation de la base de données.

Chaque groupe devra s'inscrire et saisir l'ensemble des musiciens.
Un groupe se distinguera par un nom, une catégorie de musique, un pays d'origine, un email de contact, une ou plusieurs photos, une description, des instruments qui le composent et d'un tarif de prestation en euros.
Un musicien peut appartenir à plusieurs groupes.
Chaque musicien aura également sa propre fiche avec son nom et prénom, un descriptif ainsi qu'une liste des instruments qu'il sait jouer.
Attention, certains groupes peuvent jouer des instruments, même s'il n'ont pas de musiciens!

Le second sprint est déjà en train d'être planifié afin de réaliser la gestion des lieux et du planning des concerts.


## Production attendue

Le rendu sera à faire sous la forme d'un document word dans lequel apparaîtra la modélisation du premier sprint:

- Un dictionnaire de données
- Schéma entité/association (à réaliser de façon manuscrite ou avec un outil)
- Schéma physique de la base de données

L'ensemble des données devra être stocké au sein d'une base de données relationnelle (modèle entité/Association).
Une fois cette modélisation réalisée, vous devez réaliser le **schéma physique des données** en suivant les principes du _modèle relationnel_. Ce document sera à incorporer au dossier initial.

Selon le REAC, il vous est demandé que :

- Le schéma entité association couvre les règles de gestion sur les données.
- Le schéma respecte le formalisme du modèle entité/association.
- Le schéma physique de la base de données est normalisé.

Ce rendu est à envoyer à l'adresse mail suivante : codeacademie@fondationface.org.
