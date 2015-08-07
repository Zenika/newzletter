
![Zenika](http://www.zenika.com/images/signature/simple.png)


#NewZLetter 
#####Juillet 2015
---

*Distribution mensuelle de stimulus techniques* 



## Livre : Learning Spark - Ed. O'Reilly
###Auteurs : Holden Karau, Andy Konwiski, Patrik Wendell, Matei Zaharia

Pendant ces derniers mois j'ai suivi pas mal de MOOC sur des sujets liés au *Big Data*. Le dernier en date était une introduction au Big Data avec Spark. Pour aller plus loin, je me suis acheté le livre **Learning Spark** afin d'approfondir le sujet. 

Je n'ai pas encore tout à fait terminé la lecture de l'ouvrage, mais je peux déjà donner mes impressions sur les trois quart du livre. 

Le livre est très bien, il est un bon complément à cours en ligne que j'ai suivie. Les premiers chapitres du livre se concentrent sur les concepts fondamentaux de Spark. 
Cette première partie permet de fixer les notions vue d'un point de vue pratique pendant le cours. 

Ensuite ce sont les problématiques de chargement et de sauvegarde de données. C'est un point essentiel naturellement car sans données Spark ne sert pas à grand chose :P.

Le chapitre suivant est consacré à la programmation avancée avec Spark. On découvre des *tips* de programmation que l'on peut mettre en oeuvre selon certains de use cases.

Lorsque l'on arrive à ce moment du livre, on a déjà une vision très claire de comment développer avec Spark.

Spark est un outil permettant de traiter massivement des données dans un environnement distribué.
La deuxième partie du livre commence en abordant les capacités de Spark à fonctionner dans un environnement clusterisé et également s'intégrer avec des outils de déploiement comme *Meso* ou *Yarn*.

Le livre continue son exploration en abordant les problématiques de configuration avancées et la façon de faire du debugging de programme écrit avec Spark.

La dernière partie du livre est consacrée à la présentation de 3 modules de Spark. Pour l'instant seul le module principal : Spark Core avait été abordé.

Les 3 modules sont 
- **Spark SQL** : Librairie permettant de requêter des sources de données en se basant sur la language SQL.
- **Spark Streaming** : Librairie permettant de traiter des flux en temps réel
- **Spark MLib** : Librairie dédiée au Machine Learning 

Le tour d'horizon proposé par l'ouvrage donne une vision très claire sur Spark. Le spectre couvert est large et approfondi et permet de démarrer très rapidement un projet.

Bien que l'outil soit écrit en Scala, l'outil est polyglotte. Il est possible d'écrire ses programmes sur la base de 3 langages : 

- Scala
- Python
- Java 

Etant complètement partial... Je préfère écrire mes programmes en Scala ;) plus concis, expressif, etc... (troll ;))

En résumé, un très bon ouvrage qui se lit très bien. Pas de prérequis nécessaire pour lire ce livre. Je recommande se livre à qui veut se plonger dans l'univers de Spark! 

Suite à la lecture de ce livre, j'ai commandé le livre : **Advanded Analytics with Spark** pour aller plus loin.

_Si vous avez un livre de référence intéressant n'hésitez pas à partager vos impressions ici via une issue_

---

## Breaking news

###Bientôt le nouveau blog

Le blog Zenika fait peau neuve. La pré-prod est accessible [ici](http://blog.zenika-offres.com/)

Actuellement, la nouvelle plateforme est en cours de finalisation. Il est quand même possible de se connecter à la partie admin via ce [lien](http://blog.zenika-offres.com/wp-admin)

En cas de problème, n'hésitez pas à le remonter à l'équipe marketing.


**Petit rappel du mail d'annonce envoyer récemment :**

	Pour votre photo de profil, il suffit de vous créer un compte sur gravatar avec votre adresse mail zenika : https://fr.gravatar.com/

	Nous rencontrons un problème avec les lignes de code présentes au sein des articles, un nettoyage de ces derniers est nécessaire et si vous pouviez faire un tour sur vos articles respectifs (et/ou tout autres articles qui vous bottent) afin de cleaner le code au besoin cela nous serait d'une grande aide étant donné que mes connaissances en Java se résument à un simple Hello World :)

	En parallèle de ces actions, je prépare également l'abécédaire du bon bloggeur Wordpress :) que je vous ferai parvenir par la suite.
Petite nouveauté : le blog communique avec notre compte GitHub ce qui facilitera la collaboration lors de la relecture, correction ou validation des articles. 


##MOOCs & challenges

  * [Ranger clavier et bouquins](http://s.wallpaperhere.com/wallpapers/1440x900/20110628/19741-1440x900-38155.jpg) - C'est les vacances ;)
  


##Revue de presse

 * [*Maven en couleur*](https://github.com/jcgay/maven-color) - Plus facile de décrypter les logs  
 * [*The website is unknown*](https://howdns.works/) - Explications (ludiques) du fonctionnement d'un DNS
 * [*Record and share your terminal sessions, the right way.*](https://asciinema.org/) - gratuit et efficace
 * [*Streamex*](https://github.com/amaembo/streamex) - Enrichissez l'API Stream de Java8
 * [*Top 100 des livrairies en Scala*](https://dzone.com/articles/the-top-100-scala-libraries-in-2015-based-on-64562-1?oid=top_cta) - Enrichissez l'API Stream de Java8


  

 
##Conférences

 * [*Scala World*](https://scala.world/) - Lake District 20-22 septembre 2015
 * [*Spark Summit Europe*](https://spark-summit.org/eu-2015/) - Amsterdam 27-29 octobre 2015
 * [*DDD Europe*](http://dddeurope.com/) - Brussels 28-29 janvier 2016
 * [*AWS re:Invent*](https://reinvent.awsevents.com/) - Las Vegas 6-9 octobre 2015
 * [*OSCON 2015*](http://www.oscon.com/open-source-eu-2015) - Amsterdam 24 septembre 2015
 * [*Varnish Summit Paris 2015*](https://www.eventbrite.com/e/varnish-summit-paris-tickets-17098692650) - Paris 26-28 octobre 2015
 * [*Couchbase live in France*](http://www.cvent.com/events/couchbase-live-france-2015/event-summary-059ec7a7041d401c845356bec46b7c35.aspx) - Paris 29 septembre.
 
---

##La Direction Technique

### Exercices entretiens techniques
Déjà 3 exercices ont été ajoutés dans le repo [**"entretien-technique"**](https://github.com/Zenika/entretien-technique)

Pour rappel ce repo vous fourni des exercices prêt à l'emploi pour tester vos candidats lors des entretiens techniques. Ils ne remplacent pas l'entretien oral ou théorique mais sont un excellent complément.

Merci à Manuel Verriez et Fabrice Sznajderman pour leurs exercices ainsi qu'à Ludovic Fernandez pour ses revues de code !

A vos IDE pour proposer les vôtres :)



##Le mot des tribus

### La _(nouvelle)_ tribu IoT

La tribu Multicanal est morte, vive la tribu IoT :).
Tel le Phénix, la tribu multicanal renaît des cendres qu'elle aurait pu avoir si elle était morte :)

La tribu Multicanal portait à la fois les offres d'architecture multicanal, de développement mobile et autres objets connectés, ainsi que la stratégie multicanale des entreprises.
Bref, trop de sujets et de flous.

On simplifie les choses pour les améliorer et on se recentre uniquement sur les développements des objets connectés : mobiles, mais aussi bornes, connected wearables, et tout autre IoT.
Et pour accompagner ce lifting, on adapte le nom pour devenir la Tribu IoT :)

Quant à l'architecture, ben il y a une très bonne tribu pour ça désormais ;)
 
##Les stats du Blog
#####juillet 2015 (top15)

Titre de page |	Pages vues	| Consultations uniques
--------------|-------------|--------------------
Setting up a development environment using Docker and Vagrant - Zenika|7925|6957
Documenting a REST API with Swagger and Spring MVC - Zenika|5326|4869
Premiers pas avec ElasticSearch (Partie 1) - Zenika|2576|2256
REST Web Services testing with Spring MVC - Zenika|1836|1726
Using Tomcat JDBC connection pool in a standalone environment - Zenika|1741|1602
Tutoriel sur l'installation et la configuration d'ElasticSearch (partie 1)|1272|1149
A Full Javascript Architecture, Part One - NodeJS - Zenika|1117|1024
Using Thymeleaf with Spring MVC - Zenika|963|895
Introducing Spring MVC test framework - Zenika|835|792
AngularJS : Les directives - Zenika|797|742
Java 8 et les Lambda - Zenika|642|602
Testing SQL queries with Spring and DbUnit, part 1 - Zenika|630|585
HATEOAS paging with Spring MVC and Spring Data JPA - Zenika|601|558
Premier aperçu d'AngularJS 2.0 - Zenika|552|512
Introducing the Thymeleaf template engine - Zenika|517|491


##LoL

 * [9 Funniest Code Comments by Programmers](http://www.itaxsmart.com/9-funniest-code-comments-by-programmers/) - Commenter qu'ils disaient...
 * [*RFC for the 7XX Range of HTTP Status codes - Developer Errors*](https://github.com/joho/7XX-rfc) - Et pourquoi pas ? :) 
 * [34 CSS Puns That’ll Make You Laugh... ](http://digitalsynopsis.com/design/34-css-puns-web-design-funny-jokes/) - ...Even If You Aren’t A Web Designer !

 
