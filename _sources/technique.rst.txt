Documentation technique
========

Back-end
---------

Python est un langage de programmation interprété, multi-paradigme et multiplateformes. Il favorise la programmation impérative structurée, fonctionnelle et orientée objet.

Front-end
---------

Nous avons choisi les technologies suivantes pour la partie mobile :

React Native
Nous avons choisi React Native et non Flutter ou Ionic car dans un premier temps 2 personnes du groupe ont déjà travaillé avec React Native durant des projets personnels mais également durant leur alternance. De plus, l’un des avantages de React Native est la vitesse de développement, grâce à un moteur JavaScript qui fait appel aux instances natives, les développeurs ne développent qu'une seule base de code pour les plateformes iOS et Android.

Expo
Nous avons fait le choix d’utiliser l’outil Expo qui est une surcouche à React Native qui propose de nombreux d’avantages : 
Des composants prêts à l’emploi compatible sur Android et IOS (caméra, notifications, ...)
Un système de déploiement simplifié.
OTA (Over the Air Update) qui permet de mettre à jour l’application sans avoir à passer par les stores d’applications.

React Native Testing Librairy & Jest
Nous avons fait le choix de ces deux librairies pour effectuer nos tests unitaires et intégration car elles sont très utilisées dans le monde React Native / JavaScript. De plus, elles sont bien documentées et de nombreux tutoriels existent sur internet.

Nous avons utilisé Prettier et ESLint pour les règles de syntaxe et d’indentation du code en s’inspirant de la configuration du “linter” de AirBnB. ESLint s’assure de la qualité du code (ex: obligation d’utiliser des arrow functions…) et Prettier s’occupe 

Base de données
---------

Concernant le choix de la base de données, nous avons opté pour une base de données SQLite. En effet, notre application mobile ne nécessitant pas le besoin d’une base de données complexe. Nous avons seulement besoin de stocker les réductions ainsi que les articles.
