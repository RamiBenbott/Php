Php
===
PHP: Hypertext Preprocessor3, plus connu sous son sigle PHP (acronyme récursif), 
est un langage de programmation libre4 principalement utilisé pour produire des pages Web dynamiques via un serveur HTTP3,
mais pouvant également fonctionner comme n'importe quel langage interprété de façon locale. PHP est un langage impératif
orienté objet comme C++.
Historique:
Le langage PHP fut créé en 1994 par Rasmus Lerdorf pour son site web. C'était à l'origine une bibliothèque logicielle 
en C5 dont il se servait pour conserver une trace des visiteurs qui venaient consulter son CV. Au fur et à mesure qu'il
ajoutait de nouvelles fonctionnalités, Rasmus a transformé la bibliothèque en une implémentation capable de communiquer
avec des bases de données et de créer des applications dynamiques et simples pour le Web. Rasmus décida alors en 1995 de 
publier son code, pour que tout le monde puisse l'utiliser et en profiter. PHP s'appelait alors PHP/FI (pour Personal
Home Page Tools/Form Interpreter). En 1997, deux étudiants, Andi Gutmans et Zeev Suraski, redéveloppèrent le cœur de PHP/FI. Ce travail aboutit un an plus tard à la version 3 de PHP, devenu alors PHP: Hypertext Preprocessor. Peu de temps après, Andi Gutmans et Zeev Suraski commencèrent la réécriture du moteur interne de PHP. Ce fut ce nouveau moteur, appelé Zend Engine - le mot Zend est la contraction de ZEev et aNDi - qui servit de base à la version 4 de PHP6.

En 2002, PHP est utilisé par plus de 8 millions de sites Web à travers le monde7, en 2007 par plus de 20 millions8 et
en 2013 par plus de 244 millions9.

La version actuelle est la version 5, sortie le 13 juillet 200410. Elle utilise Zend Engine 2 et introduit une 
modélisation objet plus performante, une gestion des erreurs fondée sur le modèle des exceptions, ainsi que des 
fonctionnalités de gestion pour les entreprises. PHP 5 apporte beaucoup de nouveautés, telles que le support de 
SQLite ainsi que des moyens de manipuler des fichiers et des structures XML basés sur libxml2 :

une API simple nommée SimpleXML ;
une API Document Object Model assez complète ;
une interface XPath utilisant les objets DOM et SimpleXML ;
intégration de libxslt pour les transformations XSLT via l'extension XSL ;
une bien meilleure gestion des objets par rapport à PHP 4, avec des possibilités qui tendent à se
rapprocher de celles de Java.
La dernière mise à jour est la 5.6.3 datant du 13 novembre 201411.

Depuis juin 2011 et le nouveau processus de livraison de PHP, le cycle de livraison de PHP est d'une 
mise à jour annuelle comportant des changements fonctionnels importants, la durée de vie d'une branche
est de 3 ans et trois branches stables sont maintenues. Cela signifie que lorsqu'une nouvelle version de PHP 5.x
sort
, la version 5.x-3 n'est plus supportée.

Depuis la sortie de PHP 5.6, la configuration est :

branche de développement : 5.7 ;
branches encore supportées (corrections de bugs et de la sécurité) : 5.6, 5.5 ;
branche en obsolescence et ne recevant que des correctifs de sécurité : 5.4 ;
toutes les branches < 5.4 ne sont plus supportées.
Il est à noter qu'historiquement, PHP disposait d'une configuration par défaut privilégiant la souplesse à la
sécurité (par exemple register globals, qui a été activé par défaut jusqu'à PHP 4.212). Cette souplesse à permis à
de nombreux développeurs d'apprendre PHP mais le revers de la médaille a été que de nombreuses applications PHP
étaient mal sécurisées. Le sujet a bien été pris en main par le PHPGroup qui à mis en place des configurations par
défaut mettant l'accent sur la sécurité. Il en résultait une réputation de langage peu sécurisé, réputation 
d'insécurité qui n'a plus de raison d'être.

n 2005, le projet de faire de PHP un langage supportant et fonctionnant nativement en Unicode a été lancé par Andrei Zmievski, ceci en s'appuyant sur la bibliothèque International Components for Unicode (ICU) et en utilisant UTF-16 pour représenter les chaînes de caractères dans le moteur63.

Étant donné que cela représentait un changement majeur tant dans le fonctionnement du langage que dans le code PHP créé par ses utilisateurs, il fut décidé d'intégrer cela dans une nouvelle version 6.0 avec d'autres fonctionnalités importantes alors en développement64. Toutefois, le manque de développeurs experts en Unicode ainsi que les problèmes de performance résultant de la conversion des chaînes de et vers UTF-16 (rarement utilisé dans un contexte web), ont conduit au report récurrent de la livraison de cette version65. Par conséquent, une version 5.3 fut créée en 2009 intégrant de nombreuses fonctionnalités non liées à Unicode qui était initialement prévues pour la version 6.0, notamment le support des espaces de nommage (namespaces) et des fonctions anonymes. En mars 2010, le projet 6.0 intégrant unicode fut abandonné et la version 5.4 fut préparée afin d'intégrer la plupart des fonctionnalités non liées à l'unicode encore dans la branche 6.0, telles que les traits ou l'extension des closures au modèle objet66.

Le projet est depuis passé à un cycle de livraison prévisible (annuel) contenant des avancées significatives mais contenues tout en préservant au maximum la rétro-compatibilité avec le code PHP existant (5.4 en 2012, 5.5 en 2013, 5.6 prévue pour l'été 2014). Depuis janvier 201467, l'idée d'une nouvelle version majeure introduisant Unicode mais se basant sur UTF-8 (largement devenu depuis le standard du Web pour l'Unicode) et permettant certains changements pouvant casser la rétro-compatibilité avec du code PHP ancien est de nouveau discutée et les RFC sont maintenant triées selon leur implémentation en 5.x (évolutions ne causant pas ou marginalement de cassure de la rétro-compatibilité) ou dans la future version majeure (évolutions majeures du moteur et évolutions impliquant une non-compatibilité ascendante).
