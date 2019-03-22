

## Les patrons de conception

Il existe trois familles de patrons de conception selon leur utilisation :

**créateurs :** ils définissent comment faire *l'instanciation et la configuration des classes et des objets* ;
**structuraux :** ils définissent *comment organiser les classes d'un programme dans une structure plus large* (séparant l'interface de l'implémentation) ;
**comportementaux :** ils définissent comment organiser les objets pour que ceux-ci collaborent (distribution des responsabilités) et expliquent le fonctionnement des algorithmes impliqués.

## Factory et abstract factory

Ce patron fournit une interface pour créer des familles d'objets sans spécifier la classe concrète. Le patron factory (en français fabrique) est un patron récurrent. Une fabrique simple retourne une instance d'une classe parmi plusieurs possibles, en fonction des paramètres qui ont été fournis. 

## Adapter

Ce patron convertit l'interface d'une classe en une autre interface exploitée par une application. Permet d'interconnecter des classes qui sans cela seraient incompatibles. 


## Chain of responsibility

Ce patron vise à découpler l’émission d'une requête de la réception et le traitement de cette dernière en permettant à plusieurs objets de la traiter successivement. 

## Command

Ce patron emboîte une demande dans un objet, permettant de paramétrer, mettre en file d'attente, journaliser et annuler des demandes. Dans ce patron un objet command correspond à une opération à effectuer. L'interface de cet objet comporte une méthode execute.

## Composite

Ce patron permet de composer une hiérarchie d'objets, et de manipuler de la même manière un élément unique, une branche, ou l'ensemble de l'arbre. Il permet en particulier de créer des objets complexes en reliant différents objets selon une structure en arbre. 

## Decorator

Ce patron permet d'attacher dynamiquement des responsabilités à un objet. Une alternative à l'héritage. Ce patron est inspiré des poupées russes. Un objet peut être caché à l'intérieur d'un autre objet décorateur qui lui rajoutera des fonctionnalités, l'ensemble peut être décoré avec un autre objet qui lui ajoute des fonctionnalités et ainsi de suite. 

## Façade

Ce patron fournit une interface unifiée sur un ensemble d'interfaces d'un système. Il est utilisé pour réaliser des interfaces de programmation.

## Iterator

Ce patron permet d'accéder séquentiellement aux éléments d'un ensemble sans connaitre les détails techniques du fonctionnement de l'ensemble. C'est un des patrons les plus simples et les plus fréquents. 

## Observer

Ce patron établit une relation un à plusieurs entre des objets, où lorsqu'un objet change, plusieurs autres objets sont avisés du changement. Dans ce patron, un objet le sujet tient une liste des objets dépendants des observateurs qui seront avertis des modifications apportées au sujet. 

## Prototype

Ce patron permet de définir le genre d'objet à créer en dupliquant une instance qui sert d'exemple - le prototype. L'objectif de ce patron est d'économiser le temps nécessaire pour instancier des objets. 

## Proxy

Ce patron est un substitut d'un objet, qui permet de contrôler l'utilisation de ce dernier. Un proxy est un objet destiné à protéger un autre objet. Le proxy a la même interface que l'objet à protéger. Un proxy peut être créé par exemple pour permettre d’accéder à distance à un objet (via un middleware).

## Singleton

Ce patron vise à assurer qu'il n'y a toujours qu'une seule instance d'une classe en fournissant une interface pour la manipuler

## Strategy

Dans ce patron, une famille d'algorithmes est encapsulée de manière qu'ils soient interchangeables. Il comporte trois rôles : le contexte, la stratégie et les implémentations. 


## Modèle-vue-contrôleur

Combinaison des patrons observateur, stratégie et composite, ce qui forme ainsi un patron d'architecture.
