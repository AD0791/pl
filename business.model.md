---
title: Project Lifecycle Business Model Element
author: Project lifecycle inc.
toc: true
output: word_document
---

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=true} -->

<!-- code_chunk_output -->

1. [1. Ebauche de Cahier des Charges](#1-ebauche-de-cahier-des-charges)
   1. [1.1. Representation graphiques (arborescence de l'application)](#11-representation-graphiques-arborescence-de-lapplication)
   2. [1.2. Raisonnement de l'applications en terme de fonctionnalites](#12-raisonnement-de-lapplications-en-terme-de-fonctionnalites)
2. [2. Mise en production de l'application](#2-mise-en-production-de-lapplication)
   1. [2.1. Resources et couts](#21-resources-et-couts)
      1. [2.1.1 Maquette](#211-maquette)
      2. [2.1.2 Le choix du Stack](#212-le-choix-du-stack)
      3. [2.1.3 Le choix de recrutement](#213-le-choix-de-recrutement)
      4. [2.1.4 L'Hebergement de l'application](#214-lhebergement-de-lapplication)

<!-- /code_chunk_output -->

# 1. Ebauche de Cahier des Charges

**Le cahier des Charges**: schémas explicatifs, maquettes fonctionnelles, logos, captures d’écrans de sources d’inspiration, images d’illustration, … Selon les projets et leur complexité sa taille peut varier d’une quinzaine à une centaine de pages

L'application est mise en place pour repondre a des besoins de gestion de projet de developpement pour toutes instances oeuvrant dans ce cadre.

le business case initiale contient deja des points preliminaires pouvant etre inclus dans ce document. ces points sont:

- Analyse de la demande
- Analyse des solutions existantes
- Analyse des limites solutions existantes
- description des fonctionnalites techniques specifiques a la gestion de projet

## 1.1. Representation graphiques (arborescence de l'application)

La maquette ou protoype de l'application sera fait avec [figma](https://www.figma.com/).

## 1.2. Raisonnement de l'applications en terme de fonctionnalites

L'utilisateur doit etre en mesure de

# 2. Mise en production de l'application

On appelle mise en production de l'application. Tout ce qui rentre dans le processus de deployement de l'application sur les services d'hebergements. ce faisant l'application sera disponible pour utilisation.

## 2.1. Resources et couts

Le processus de creation d'un logiciel comporte plusieurs phase. la premiere comprend l'etape de conceptualisation. Ici on identifie un probleme sucitant un interet clair. Ensuite on vient avec une solution pour resourdre ce probleme. La seconde phase va lui etre le chemin parcouru pour sortir de la conception a la materialisation.

Cette phase peut etre subdivisee en 4 segments fondamental.

1. Dessinage d'une maquette ou prototype.
2. le choix d'un Stack (des differents outils technologiques pour construire l'application).
3. les choix recrutements de developpeurs pour construire une premiere version de l'application.
4. Les choix possibles pour heberger l'application.

### 2.1.1 Maquette

La maquette a pour role de representer graphiquement l'arborescence de l'application. A ce niveau, on pourrait envisager les services d'un [ui/ux designer](https://www.salary.com/research/salary/posting/ux-design-intern-hourly-wages#:~:text=Hourly%20Wage%20for%20UX%20Design%20Intern%20Salary%20in%20the%20United%20States&text=How%20much%20does%20a%20UX,falls%20between%20%2431%20and%20%2439). Mais l'equipe peut aussi faire le choix de faire un design preliminaire avec des outils gratuits tel que figma.

> Cout eventuel: 27\$ dollars de l'heure pour le UI/UX designer (prix minimal basee sur le marchee americain). En faisant ce choix, on s'assoit deja sur les problemes du good looking de l'interface d'utilisateur et de l'experience d'utilisateur.

### 2.1.2 Le choix du Stack

Le choix du Stack se fera ressentir en 2 moments. Apres avoir obtenu une maquette representant une version beta de l'application. On peut bien vouloir cette version beta heberger donc disponible sur le web pour une utilisation minimal. Nous disons minimal puisque nous n'aurons pas implementer toutes les features a ce stade.

La version beta de l'application peut etre developpe soit par les associes fondateurs. Soit par les developpeurs embauchees.

> cout eventuel: Average 25.88 \$ de l'heure pour un developpeur

Mais le choix en soit du stack ne necessite casiment aucun cout reel. Puisqu'ils sont tous open-source. Oubien ils ont un forfait gratuit que nous pouvons utiliser.

### 2.1.3 Le choix de recrutement

Cette equipe choisira le meilleur mode developpment pour l'application.

- Monolythique
- Microservice

Ce choix de developpement sera fait aussi pour la version beta de l'application

> cout eventuel:

- marche americain: verage 25.88 \$ de l'heure
- [outsourcing](https://medium.com/@siriannimatthew435/best-outsourcing-software-companies-software-development-firms-in-india-usa-cd2cf40710a0) : 20-49 \$ de l'heure
- Haiti: 5-35 \$ de l'heure

### 2.1.4 L'Hebergement de l'application

Pour le moment, nous portons notre choix sur Microsoft Azure. De ce faite, si on choisit d'utiliser un service virtual machine pour deployer l'application.

Dependemment des specificites de l'instance selectionnee on peut:

> cout eventuel:

- [prix maximal](https://azure.microsoft.com/en-us/pricing/calculator/) 5.184 \$ / hr -> \$3,784.37 Average per month
- [prix minimal](https://azure.microsoft.com/en-us/pricing/calculator/) 0.117\$ / hr -> \$85.46 Average per month

Il faut dire que ces prix vont varier en fonction de l'utilisation du VM en question. Donc on peut prendre le prix minimal dans ce context.
