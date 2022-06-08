# Travailler à plusieurs : pair et mob programming

## C'est quoi ?

Développer une nouvelle fonctionnalité en pair ou en mob programming, cela signifie **travailler à deux ou à plusieurs sur la fonctionnalité, avec un seul clavier et écran**.

Le **pair-programming** (ou programmation en binôme) consiste à être deux devs sur un même poste de travail.

Le **mob-programming** consiste à être au moins trois ou plus sur un même poste de travail à travailler sur la fonctionnalité.

Ces pratiques font partie des pratiques d'[Extreme Programming](https://fr.wikipedia.org/wiki/Extreme_programming).

## Pourquoi ?

Ces pratiques permettent d'utiliser l'intelligence collective autour d'un sujet.

Nous pouvons noter en aspect positifs de ces pratiques :
* le partage de connaissances et de bonnes pratiques au sein des équipes
* la production de code de meilleure qualité
* aide à la montée en compétence de tous les devs
* permet de challenger ses connaissances et ses compétences

De plus, cela :
* réduit le temps de review des fonctionnalités, plusieurs personnes ayant déjà vu le code : le code va donc plus rapidement en production
* évite de s'éparpiller sur d'autres sujets

Sur un aspect social, cette activité :
* permet d'améliorer ses compétences sur le travail en équipe
* améliore la communication et la confiance au sein des équipes
* évite qu'une personne se sente isolée


## En pratique

Le pair et le mob programming sont possibles dans les bureaux ou à distance (en remote).

### S'organiser

Dans les deux cas, il est important de bien s'organiser avant de démarrer le pair ou le mob :
* Préparer une branche Git partagée
* Tous les participants ont déjà tout ce qu'il faut en local et on déjà lancé ce qu'il faut

Pour le bon déroulé de l'activité, il faut aussi : 
* Se mettre d'accord sur le sujet et l'objectif
* Expliquer la problématique à tout le groupe
* Indiquer le fonctionnement (durée des tours, durée totale, pause, rôles et qui prend après qui)
* Commit et push souvent sur la branche partagée
* Faire des pauses

### Les rôles possibles

Durant un pair-programming, il peut y avoir deux rôles :
* un.e driver.e : rédige le code
* un.e observeur.se : assiste et suggère des alternatives

Pour un mob-programming, nous pouvons retrouver d'autres rôles : 
* un.e driver.e : responsable du clavier, il code dans la direction donnée par le navigateur
* mob : le groupe donne son avis au navigateur
* un.e navigateur.rice : compile les avis et donne les directions au driver

Les rôles doivent être échangés régulièrement.

### Fonctionnement globale

Que ce soit le pair ou le mob, il est important d'ête clair sur le fonctionnement globale, et notamment : 
* La durée de l'activité : travailler à plusieurs sur un sujet peut demander beaucoup d'énergie, c'est important de savoir quand on s'arrête et de prévoir des pauses régulièrements
* les rôles et les tours de rôles : une fois que les rôles présents ont été décidé, il est important d'indiquer la durée d'un tour dans un rôle.

Nos conseils :
* Faire tourner les rôles toutes les 15 minutes environ
* Prévoir une pause de 10/15 minutes toutes les heures
* Ne pas dépasser 3 ou 4h de mob

### A noter :

Cette activité n'est pas toujours facile à bien animer. Il est important d'en faire régulièrement, possiblement sur des fonctionnalités plus petites, ou lors de Kata.
Cela peut être source de stress ou de complexe. Chaque membre de l'équipe doit faire preuve d'écoute, de bienveillance et d'humilité.

Il peut arriver que certaines personnes n'arrive pas à suivre, il faut alors : 
* l'indiquer au groupe
* prendre le temps de réexpliquer la problématique, notamment en revenant de pause
* changer de rôle si besoin

## Quand en faire ?

Il est possible d'en faire sur tous les tickets, mais cela peut déprendre des disponibilités des membres des équipes.

La pratique de développement à plusieurs est **fortement recommandée** : 
* Lors du démarrage d'un nouveau chantier
* Lors de grosse fonctionnalités
* Lors de fonctionnalités entre plusieurs équipes, pour travailler avec des membres de différentes équipes
* Lors de chantiers où l'équipe manque de connaissance ou compétence

### Et quand ne pas en faire ?

* Lorsqu'il y a des tensions entre certains membres de l'équipe : les sessions de pair ou de mob peuvent être douloureuse, c'est important de remonter alors la situation aux Lead Dev et aux Managers pour solutionner ces tensions
* Lorsque la tache est trop simple ou trop maitrisée par l'équipe : cela serait une perte de temps

## Ressources :

* [Mob Programming and the Power of Flow • Woody Zuill](https://www.youtube.com/watch?v=28S4CVkYhWA)
* [Woody Zuill - No Estimates, Mob Programming and More](https://www.youtube.com/watch?v=O3N7kEeor70)

