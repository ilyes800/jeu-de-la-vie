# Jeu de la vie de Conway

**Projet de conception et programmation orientée objet · CESI · Deuxième année**

## Objectif

Développer en C++ une simulation du Jeu de la vie : des cellules évoluent sur une grille selon des règles de naissance, de survie et de disparition. L’objectif est de séparer la logique de la simulation de son affichage et de mettre en pratique les principes de la programmation orientée objet.

![Évolution de la grille à partir des générations exportées](evolution.gif)

*Aperçu créé à partir des fichiers de générations fournis avec le projet. Il représente les données exportées, pas une capture de l’interface SFML.*

## Fonctionnalités

La version finale dispose d’un mode console et d’un mode graphique avec SFML. Elle permet de charger une grille depuis un fichier, de faire évoluer les cellules et d’exporter les générations. En mode graphique, le clavier permet de mettre en pause, d’avancer d’une génération ou de revenir à l’état initial.

| Touche | Action |
| --- | --- |
| Espace | Lecture ou pause. |
| N | Génération suivante. |
| R | Rechargement de la grille initiale. |
| Échap | Fermeture de la fenêtre. |

## Technologies et conception

C++, SFML, STL, UML, Git et GitHub. L’architecture distingue les cellules, leurs états, les règles d’évolution, la grille et l’affichage. Elle utilise l’héritage, le polymorphisme et les pointeurs intelligents.

## Finalité du projet

Transformer un modèle algorithmique en une application structurée et visualisable, en travaillant la conception objet, la manipulation de fichiers et la séparation des responsabilités.

## Présentation

Cette page présente l’objectif, les fonctionnalités et la finalité du projet. L’animation illustre les générations exportées. Le code source n’est pas publié dans ce dépôt.

[Mon profil](https://github.com/ilyes800)
