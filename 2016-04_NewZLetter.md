#NewZLetter 
#####Avrils 2016
---

*Distribution mensuelle de stimulus techniques* 

## Contributeurs : 

 * **Julien Landuré**
 * **Vincent Demeester**
 * **Hervé Rivière** 
 * **Emmanuel DEMEY**

##Mettez Lagom : Architecture micro-service réactive

Au mois de mars, Lightbend (ex typesafe) sortait son framework de microservice. Un de plus me direz-vous? oui peut être.. mais car il y a toujours un mais :) Ce framework propose quelques petites choses intéressantes. Je vous propose dans ce cours article de faire le point!
Le créateur du Lagom, *Jonas boner*, met en avant les points suivants pour parler de son framework et décrire les différenciateurs par rapport à l'écosystème existant : 

 * par défaut la communication est asynchrone entre chaque service. Evidemment, il est possible de faire du synchrone également si nécessaire. 
 * côté persistence, le framework se base sur les patterns d'**Event sourcing** et **CQRS**. Par défaut.
 * Lagom offre un environnement de développement ou l'on peut travailler efficacement. C'est-à-dire que l'on peut démarrer l'ensemble de ses microservices à l'aide d'une seule commande. Au lancement, Lagom lance une base Cassandra (embeded, un service locator et un service gateway, par défaut. 
 * Lagom supporte le rechargement à chaud du code après modification. 
 
*(liste non exhaustive)*
 D'une manière générale, Lagom a été bati selon les principes réactifs (décrit dans le [reactive manifesto](http://www.reactivemanifesto.org/).

D'un point de vue technique, la première version de Lagom est développée sur une base Java. Néanmoins, lorsque l'on rentre dans les entrailles de la bête, on croise du code Scala (ouf ! :) ).
Prochainement, une version Scala sera proposée. 

Lagom met en oeuvre pas mal de librairies externes pour adresser les différentes problématiques techniques. Voici une liste des librairies que l'on peut trouver : 



Librairie |	  Objectif |
---------|-------------|
Immutable| Objet immuable |
Play framework| Web |
SBT      |  Build |
Guice    | IOC |
Akka   | Clustering, message, Stream |
Akka Stream | Streaming |
SLF4J/LogBack | Logging |
Jackson | Sérialisation |
Cassandra | Stockage |
ConductR | Déploiement, service locator |

J'ai commencé à jouer avec pour découvrir et comprendre la philosophie de l'outil. Comme on peut le voir, beaucoup de concepts et de composants techniques sont utilisés, ce qui rend l'environnement riche et intéressant. 
Une fois le tour du propriétaire fait, on se rend compte que l'écriture et le déploiement d'un service sont très simple.

Le principal concurrent de ce framework serait **SpringBoot**. 

Actuellement, la documentation est vraiment centrée sur l'essentiel et on ne trouve pas tout; mais il est facile d'obtenir des informations notamment au chat mis en place sur Gitter ou l'on peut discuter facilement avec les contributeurs du projet.

Le projet est accessible [ici](https://www.lightbend.com/lagom). Si le sujet vous intéresses, je vous recommande d'y jeter un oeil.

Bonne lecture!

*Si vous avez des idées pour écrire un article chapeau, sur un sujet en particulier, n'hésitez pas à l'ajouter sur github ou le faire savoir sur le channel sur slack*


##Revue de presse

 
 * [*Code smell : article sur la précense du check != null dans un block finaly*](http://www.yegor256.com/2016/03/22/try-finally-if-not-null.html) 
 * [*The fear of automation*](http://blog.codeship.com/the-fear-of-automation/)
 * [*Tutoriel sur la compréhension de la machine virtuelle Java 1*](http://soat.developpez.com/tutoriels/java/jvm/decouverte-machine-virtuelle-java/?page=l-unicode-et-java) 
 * [*Tutoriel sur la compréhension de la machine virtuelle Java 2*](http://sqli.developpez.com/tutoriels/java/machine-virtuelle-java/) 
 * [*Reactivex.io*](http://reactivex.io/rxjs/manual/overview.html) 
 * [*Java est il toujours aussi lent ? :)*](http://www.developpez.com/actu/97302/Si-Java-est-considere-par-plusieurs-professionnels-comme-etant-lent-et-lourd-le-framework-web-le-plus-rapide-selon-TechEmpower-est-ecrit-en-Java/) 
 * [*Création de la Fondation du Centre Scala*](http://www.infoq.com/fr/news/2016/03/scala-centre) 
 * [*Predictions for Java 20*](https://dzone.com/articles/predictions-for-java-20?utm_source=Weekly%20Digest&utm_medium=email&utm_content=DZone%20Weekly%20Digest&utm_campaign=wd%202016-03-23) 
 * [*Event Sourcing in practice*](https://ookami86.github.io/event-sourcing-in-practice/) 
 * [*Améliorations de Git*](http://www.infoq.com/fr/news/2016/03/git28-released) 
 * [*Inférence de type en Java*](http://openjdk.java.net/jeps/286) 
 * [*Javaslang core is a functional library*](http://www.javaslang.io/) 
 * [*Top Ten Front-End Design Rules For Developers*](https://www.toptal.com/front-end/front-end-design-principles?utm_campaign=blog_post_front_end_design_principles&utm_medium=email&utm_source=blog_subscribers) 
 * [*Pourquoi je n'utilise plus de Frameworks MVC*](http://www.infoq.com/fr/articles/no-more-mvc-frameworks?utm_content=buffera19a6&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer) 


##Conférences

###Les Mardis du Web - Zenika Lille

Depuis un peu plus d'un mois, nous avons mis en place **les Mardi du Web** chez **Zenika Lille**. 

Le but est de proposer des mini conférences, afin de présenter différents sujets liées à la meilleure des tribus. Deux rendez-vous ont déjà eu lieu : 
 * le premier autour de l'approche Mobile-First (avec en invité [Angéla Ricci](https://twitter.com/gericci)), 
 * le second autour de Wordpress (présenté par [Aurélien Loyer](https://twitter.com/T3kstiil3))


## Vidéos ZenikaTV 

Suite du CFV #2, et la sortie d'une nouvelle vidéo [**"Qu'apporte Angular2 ?"** par **@Emmanuel Demey**](https://www.youtube.com/watch?v=lQFBocpFDBA)

*Tout le monde connait AngularJS, et tout le monde a entendu au moins une fois parler de sa prochaine version. Après un début assez difficile, cette nouvelle version propose de nombreuses fonctionnalités très intéressantes, permettant de développer des applications robustes, de meilleure qualité et plus rapidement.

Présentation de trois fonctionnalités à connaître pour vos prochains développements.*
Merci de RT ;)

*Une question ? Contactez Marketing & Julien Landuré*



---

##Les stats du Blog
#####Avril 2016 (top 15)

Titre de page |	Pages vues	| Consultations uniques
--------------|-------------|--------------------

**HTTP 404** - *Stats not found this month! :-/*


##LoL

 * [How Standards proliferate](https://medium.com/javascript-and-opinions/state-of-the-art-javascript-in-2016-ab67fc68eb0b#.xq2460z4v)
 * [quand je fais un update sans where sur la base de prod ](http://lesjoiesducode.fr/post/138278553968/quand-je-fais-un-update-sans-where-sur-la-base-de#_=_)
