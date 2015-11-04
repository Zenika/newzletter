
![Zenika](http://www.zenika.com/images/signature/simple.png)


#NewZLetter 
#####Octobre 2015
---

*Distribution mensuelle de stimulus techniques* 


## SBT : Simple Build Tool

Dernièrement j'ai posé à slack la question suivante : "Est ce que quelqu'un connait/utilise SBT?"

Je n'ai qu'une réponse qui m'indiquait qu'il y a eu une personne qui utilisait cet outil, mais elle n'était plus là pour en parler. La communauté ayant été peu loquace sur le sujet, je me dis l'outil est peut-être méconnu alors je vous propose un tour d'horizon.

Si l'on fait un rapide historique des outils de build, on va d'abord tomber sur les bon vieux scripts fait à la main spécifique à chaque projet et qui souffrait d'un problème de portabilité (en autre).
 
Pour pallier à ces problèmes, un premier outil a fait son apparition  Ant. Développé en Java, il a permis de rentre le build portable sur les différents Os du marché. Ant a apporté également la possibilité de structurer et rationaliser la structure des builds, sans apporter de vrai standards cross projet.

C'est Maven qui a introduit une structure et un cycle de vie standard à l'ensemble de projet l'utilisant. D'ailleurs Maven est devenu une référence incontournable aujourd'hui en matière d'outil de build.

Aujourd'hui d'autres outils émergent et proposent des fonctionnalités équivalentes et plus encore. Parmis ces challengers on trouve Gradle et SBT. 

Les principaux objectifs de ces deux outils sont, sur le papier, les mêmes : 

 - Simplification pour étendre l'outil
 - Fournir un DSL pour la configuration du build
 
Bon vous vous en douterez, SBT apporte in-fine plus de choses que Gradle. :) C'est normal, c'est un article sur SBT. 
Plus sérieusement, bien que Gradle améliore grandement la situation par rapport à Maven, SBT va plus loin ne se limitant pas juste à construire le livrable d'un projet.

En effet, SBT s'intègre dans le workflow de développement en proposant des features vraiment très pratique au quotidien : 
 
 - **Continuous testing** : Exécute les tests en continu à chaque modification du code source. Seulement les tests concernés. 
 - **Console interactive** : Console permettant d'exécuter du code à la volée avec l'ensemble des classes du projet disponible.
 - **Cross-compilation** : Il est possible de définir la version du compilateur cible. SBT se charge du reste.
 - **Sécurité du typage** : SBT fournit un DSL basé sur le language Scala. Celui-ci vient naturellement avec le typage fort du language.
 - **Simplicité d'extension** : Tout est tâche dans SBT, l'écriture d'une tâche est simple, rapide et intégré au projet.
 
La liste des fonctionnalité est loin d'être exhaustive mais donne déjà un aperçu des possibilités offertes par l'outil.

Même si, la connaissance approfondie de Scala n'est pas nécessaire, il faut quand même avoir quelques notions. 

Sbt est capable de packager autant du code Scala que du code Java. SBT possède également deux plugins permettant la génération des fichiers de configuration pour les principaux IDE (comme Eclipse ou IDEA)
 
En terme de convention de structure de projet, SBt se base sur les conventions mises en place par Maven.

SBT se base sur le gestionnaire de dépendance Ivy2.

Aujourd'hui, SBt n'est pas encore sortie en version majeure, mais celle-ci devrait être releasée sous peu
 
 






##MOOCs & challenges

  * [*HTML5 from W3C*](https://www.edx.org/xseries/html5-w3c) - Improve your web development
  * [*Introduction to Computational Thinking and Data Science*](https://www.edx.org/course/introduction-computational-thinking-data-mitx-6-00-2x-2) 

##Revue de presse

 * [*12 règles pour écrire du JS*](http://www.developpez.com/actu/90422/Un-developpeur-enonce-les-12-regles-a-respecter-pour-ecrire-un-code-JavaScript-professionnel/) - suivez le guide...  
 * [*Erik Meijer: AGILE must be destroyed, once and for all*](http://www.theregister.co.uk/2015/01/08/erik_meijer_agile_is_a_cancer_we_have_to_eliminate_from_the_industry/) - Attention!! sujet polémique
 * [*Oracle se désintéresse de Java ?*](http://www.infoworld.com/article/2987529/java/insider-oracle-lost-interest-in-java.html#tk.twt_ifw) - Qu'en est il?
 * [*Git 2.6 disponible*](http://www.developpez.com/actu/90623/Git-2-6-est-maintenant-disponible-en-telechargement-avec-des-dizaines-de-nouvelles-fonctionnalites-et-des-corrections-de-bogues/) - Découvrez le détail de cette nouvelle version
 * [*Spark : testing*](http://blog.cloudera.com/blog/2015/09/making-apache-spark-testing-easy-with-spark-testing-base/) - Tester facilement votre Spark
 * [*Tollé autour des nouvelles IntelliJ*](* [*Spark : testing*](http://blog.cloudera.com/blog/2015/09/making-apache-spark-testing-easy-with-spark-testing-base/) - Tester facilement votre Spark) - Erreur marketing ?
 * [*Lean It Summit : Incubateur de Startups au Gouvernement*](http://www.infoq.com/fr/news/2015/09/lean-it-summit-pierre-pezziardi) - Ca bouge au gouvernement 


  

 
##Conférences

 * [*WebGL Paris*](http://www.webglparis.com/) - Paris 12 octobre 2015
 * [*Paris Web*](http://www.paris-web.fr/) - Paris 1-2 octobre 2015
 * [*DroidCon*](http://droidcon.fr/) - Paris 9-10 novembre 2015
 * [*Blend Web Mix*](http://www.blendwebmix.com/) - Lyon 28-29 octobre 2015 
 * [*Codeur en Seine*](http://www.codeursenseine.com/2015/) - Rouen 26 novembre 2015 
 * [*Google Next 2015*](https://cloudplatformonline.com/NEXT_Google_Cloud_Platform_Experience_Paris.html) - Paris - 13 octobre 2015

 
 
---


##Le mot des tribus

*silence radio ce mois-ci ;)*
 
##Les stats du Blog
#####Septembre 2015 (top 15)

Titre de page |	Pages vues	| Consultations uniques
--------------|-------------|--------------------
Setting up a development environment using Docker and Vagrant - Zenika|4690|4307
Documenting a REST API with Swagger and Spring MVC - Zenika|4262|3907
Premiers pas avec ElasticSearch (Partie 1) - Zenika|2471|2191
REST Web Services testing with Spring MVC - Zenika|1893|1752
Using Tomcat JDBC connection pool in a standalone environment - Zenika|1637|1540
Zenika - Home|1578|1193
A Full Javascript Architecture, Part One - NodeJS - Zenika|1341|1235
Tutoriel sur l'installation et la configuration d'ElasticSearch (partie 1)|1095|976
Introducing Spring MVC test framework - Zenika|1016|965
Elasticsearch 2.0: ce qui change - Zenika|883|794
Java 8 et les Lambda - Zenika|877|828
Using Thymeleaf with Spring MVC - Zenika|829|785
AngularJS : Les directives - Zenika|747|703
HATEOAS paging with Spring MVC and Spring Data JPA - Zenika|701|643
Testing SQL queries with Spring and DbUnit, part 1 - Zenika|685|634


##LoL

 * [Tuto : L'art de programmer salement](http://www.developpez.net/forums/d1428236/club-professionnels-informatique/taverne-club-humour-divers/tutoriel-l-art-programmer-salement/) - Une fois que l'on sait programmer salement, plus facile de coder proprement

 
