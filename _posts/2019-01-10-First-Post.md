---
layout: post
title: Développement multiplateforme
subtitle: Parce que c'est plus simple de n'écrire le code qu'une seule fois
image: /img/Computer-mini.jpg
tags: [edito]
comments: true
published: true
---
Quand un développeur veut créer un programme, un jeu, n'importe quoi... il est important, au préalable, de savoir à partir de quels périphériques il est souhaitable qu'il soit exécuté. Si on ne pense pas à celà avant de commencer, on peut parfois se trouver confronter à des problèmes de compatibilités, ce qui peut être gênant, notamment si on travaille sur un projet pour un client (qui, de surcroît, est susceptible de changer d'avis au milieu du projet, mais c'est une autre histoire) !


Quand on est développeur, on voudrait, quoi qu'il en soit, que ce qu'on développe puisse être exécuté depuis n'importe où, sans soucis, sans écrire du code spécifique qui nous ferait perdre du temps, de la façon la plus simple, rapide... qui soit. Ce qui n'est pas toujours possible, surtout quand on souhaite une compatibilité mobile, par exemple.


De même, on voudrait bien pouvoir avoir une application qui, quand elle est multiplateforme, est ce qu'on appelle *pixel-perfect* entre les différentes plateformes. C'est-à-dire que l'application sera la même, au pixel près d'une plateforme à une autre. Elle se comportera exactement de la même façon et il n'y aura aucune différence à l'écran.


De plus, on aime bien pouvoir faire des essais sans perdre de temps, ou alors faire des démonstrations de faisabilité[^1], voire, au besoin, pouvoir changer quelque chose rapidement pour déboguer ou ajouter des fonctionnalités en temps réel avec un client ou un compagnon de projet.


Il y a quelques années (pas si lointaines), il était quasiment impossible de développer une application une fois pour toutes, en laissant un *framework*[^2] quelconque s'occuper de compiler notre programme. Ou alors, en achetant des solutions extrêmement cher. Inutile de dire que pour faire des *POC*[^1], il fallait déjà dépenser pas mal d'argent.


Maintenant, certains *frameworks*[^2] gratuits ou, mieux, Open source ont commencé à émerger, se sont démocratisés et sont devenus très efficaces. Ces *frameworks*[^2], pour certains, sont soutenus par de grandes compagnies, pour d'autres, par des mécènes ou ont une communauté de personnes qui veille à ce que tout se passe bien.


Il convient également, pour ces moteurs, de savoir le moment et l'endroit où on peut les utiliser et où il ne faut surtout pas, soit pour une raison de logique de programmation, soit parce que la licence ne le permettrait pas.


Le but de ce site est de présenter certains *frameworks*[^2], de vous exposer quelques tests que j'ai pu faire, de vous donner quelques conseils sur leur utilisation et de vous donner pour certains quelques avantages à les utiliser, quelques inconvénients également.


Tant que nous y sommes, je vous exposerai également quelques problèmes qui se présentent souvent aux développeurs, que ce soit des soucis d'ordre graphique (comment habiller mon jeu de la façon la plus rapide et jolie) ou alors d'ordre algorithmique.


Normalement, vous devriez vous y retrouver un peu mieux dans la jungle de tout ce qui existe pour le développement de projets simples et multiplateformes.


À bientôt !

[^1]: [démonstration de faisabilité = *POC (Proof of Concept)*](https://fr.wikipedia.org/wiki/Preuve_de_concept)

[^2]: [Framework = infrastructure logicielle, cadre applicatif, cadre d'applications, cadriciel, socle d'applications ou encore infrastructure de développement](https://fr.wikipedia.org/wiki/Framework)