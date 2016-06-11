# TP Application Liste de Tâches

## Objectifs

Vous devrez réaliser une application web à l'aide du framework express (ou autre),
et de la base de données orienté documents MongoDB


## Introduction

Le but est de faire un gestionnaire de tâches.

* Lister les tâches.
* Ajouter une tâche.
* Modifier une tâche.
* Supprimer une tâche.

Une tâche comporte:
* id unique
* un nom
* une date limite (optionnel)
* des labels (ex: courses, voiture, etc.)


## Modélisation des données

Définir le schéma de la base en quelques phrases, avec un exemple d'entrée au format JSON. 


## Lister les tâches

Définir une route '/tasks 'qui affichera la liste des tâches.
Dans un premier temps, la route passer une liste statique de tâches sous forme de liste html.

## Ajouter une tâche

Sur la page '/tasks/', ajouter  un formulaire permettant de saisir une nouvelle tâche.
L'action enclenché ira sur la route '/tasks/new'

Hints:
* utiliser le datepicker de jquery-ui pour récupérer les dates.

## Supprimer une tâche

Ajouter un lien supprimer qui ir sur la route '/tasks/delete/<id>'.


## Afficher une tâche

Générer une page affichant une tâche à la route '/tasks/<id>'.

## Modifier une tâche

Générer un formulaire permettant de modifier une tâche
les champs devront être pré-remplis avec les informations dans la base.

Le formulaire sera affiché à la route '/tasks/<id>/edit'` et l'action sera lié à la route '/tasks/<i>' sur un verbe HTTP à déterminer.


## Notation

Tout ceux qui n'ont pas rendu le TP précédent, doivent rendre ce TP sous forme de travail individuel.

* forker le dépôt TP2-DASI2
* soumettre une pull request sur le fichier devoir,md en ajoutant une ligne au format: PRENOM NOM EMAIL URL_DEPOT
* Attention le dépôt disparaitra après dimanche minuit!

Pensez à commenter votre projet en expliquant vos choix, par rapport aux questions posées.


Vous serez noté, en fonction:

* de la _propreté_ du code (coding standards, choix de nommage, organisation du project, architecture)
* de la méthode de travail (versionning, tests, etc.)
* de la conception
* bonus pour la prise de risque (utilisation de technos différentes, petits plus)

