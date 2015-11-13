
![Zenika](http://www.zenika.com/images/signature/simple.png)


#NewZLetter 
#####Octobre 2015
---

*Distribution mensuelle de stimulus techniques* 


## SBT : Simple Build Tool

Dernièrement j'ai posé à slack la question suivante : "Est ce que quelqu'un connait/utilise SBT?"

Je n'ai eu qu'une réponse qui m'indiquait qu'il y a eu une personne qui utilisait cet outil, mais elle n'était plus là pour en parler. La communauté ayant été peu loquace sur le sujet, je me dis l'outil est peut-être méconnu alors je vous propose un tour d'horizon.

Si l'on fait un rapide historique des outils de build, on va d'abord tomber sur les bons vieux scripts fait à la main spécifique à chaque projet et qui souffrait d'un problème de portabilité (en autre).
 
Pour pallier à ces problèmes, un premier outil a fait son apparition  Ant. Développé en Java, il a permis de rendre le build portable sur les différents OS du marché. Ant a apporté également la possibilité de structurer et rationaliser la structure des builds, sans apporter de vrais standards cross projet.

C'est Maven qui a introduit une structure et un cycle de vie standard à l'ensemble de projet l'utilisant. D'ailleurs Maven est devenu une référence incontournable aujourd'hui en matière d'outil de build.

Actuellement d'autres outils émergent et proposent des fonctionnalités équivalentes et plus encore. Parmi ces challengers on trouve Gradle et SBT. 

Les principaux objectifs de ces deux outils sont, sur le papier, les mêmes : 

 - Simplification pour étendre l'outil
 - Fournir un DSL efficace pour la configuration du build
 
Bon vous vous en douterez, SBT apporte in-fine plus de choses que Gradle :). C'est normal, c'est un article sur SBT. 
Plus sérieusement, bien que Gradle améliore grandement la situation par rapport à Maven, SBT va plus loin ne se limitant pas juste à construire le livrable d'un projet.

En effet, SBT s'intègre dans le workflow de développement en proposant des features vraiment très pratiques au quotidien : 
 
 - **Continuous testing** : Exécute les tests en continu à chaque modification du code source. 
 - **Console interactive** : Console permettant d'exécuter du code à la volée avec l'ensemble des classes du projet disponible.
 - **Cross-compilation** : Il est possible de définir la version du compilateur cible. SBT se charge du reste.
 - **Sécurité du typage** : SBT fournit un DSL basé sur le language Scala. Celui-ci vient naturellement avec le typage fort du language.
 - **Simplicité d'extension** : Tout est tâche dans SBT, l'écriture d'une tâche est simple, rapide et intégré au projet.
 - **Compilation incrémentale** : Les sources ne sont pas systématiquement recompilées.
 - **Lancement des tests de manière intelligente** : Seuls les tests affectés par le code modifié seront exécutés. 
 
La liste des fonctionnalités est loin d'être exhaustive mais donne déjà un aperçu des possibilités offertes par l'outil.

Même si, la connaissance approfondie de Scala n'est pas nécessaire, il faut quand même avoir quelques notions. 

Sbt est capable de packager autant du code Scala que du code Java. SBT possède également deux plugins permettant la génération des fichiers de configuration pour les principaux IDE (comme Eclipse ou IDEA).
 
En terme de convention de structure de projet, SBt se base sur les conventions mises en place par Maven.

SBT se base sur le gestionnaire de dépendance Ivy2.

Je pense que cet outil mérite que l'on y jette un oeil. :)

[Documentation SBT](http://www.scala-sbt.org/0.13/docs/index.html)
 

##News!

Mario Loriedo présentera un talk à la conférence Codeur en Seine : *Test Driven Infrastructure avec Docker*
La conférence se tient le 26 novembre prochain.

## Call For Papers

Deux CFPs intéressants sont ouverts actuellement : 

 * [*Devoxx FR 2016*](* [*http://cfp.devoxx.fr/*](http://blog.cloudera.com/blog/2015/09/making-apache-spark-testing-easy-with-spark-testing-base/) - Cloture le 31 janvier 2016

 * [*YoungBlood III - Paris Jug*](* [*https://docs.google.com/forms/d/15E_xKcldjBXhd-t3aRiJZXaupZrRSg6hBO25aBBxv2U/viewform) - Cloture le 21 novembre 2015





##MOOCs & challenges

  * [*Learning how to learn*](https://www.coursera.org/learn/learning-how-to-learn)
  * [*Introduction to MongoDB using the MEAN Stack*](https://www.edx.org/course/introduction-mongodb-using-mean-stack-mongodbx-m101x) 

##Revue de presse

 * [*Akka Stream and Http 2.0-M1 Released!*](http://akka.io/news/2015/11/05/akka-streams-2.0-M1-released.html) - Nouvelle release! 
 * [*Learning Go (from Java)*](http://blog.loof.fr/2015/11/learning-go-from-java.html?m=1) - Go go go
 * [*Usages autour d’Ansible sur le Cloud public ou privé*](http://www.infoq.com/fr/presentations/usages-ansible-cloud-public-prive?utm_campaign=infoq_content&utm_source=infoq&utm_medium=feed&utm_term=global) - Les usages d'Ansible
 * [*Jnario : Executable Specifications for Java.*](http://jnario.org/) - Test Spécification for Java
 * [*Les transports parisiens en open data*](http://www.linformaticien.com/actualites/id/38418/les-transports-parisiens-en-open-data.aspx) - Les transports parisiens en open data
 * [*L’Entreprise Libérée pour le Développeur*](http://www.touilleur-express.fr/2015/11/04/lentreprise-liberee-pour-le-developpeur/) - Ca me dit quelque chose :)
 * [*Using a framework or not*](https://blog.frankel.ch/using-a-framework-or-not) - That is the question.
 * [*La proposition Object.observe pour ECMAScript va être abandonnée*](http://www.infoq.com/fr/news/2015/11/object-observe-withdrawn?utm_campaign=infoq_content&utm_source=infoq&utm_medium=feed&utm_term=global). - les explications 



 
##Conférences

 * [*AppsDay 2015*](http://www.appdays.fr/2015/) - Paris 25-26 novembre 2015
 * [*Code en Seine*](http://www.codeursenseine.com/2015/) - Université de Rouen 26 novembre 2015
 
 
---


##Le mot des tribus

*silence radio ce mois-ci ;)*
 
##Les stats du Blog
#####Octobre 2015 (top 15)

Titre de page |	Pages vues	| Consultations uniques
--------------|-------------|--------------------

**HTTP 404** - *Stats not found this month! :-/*

##LoL

 * [Quand j'utilise un nouveau framework](http://lesjoiesducode.fr/post/132467527961/quand-jutilise-un-nouveau-framework) - Pas toujours évident de piger du premier coup
 * [Quand quelqu'un cherche à ce que je lui donne les droits d'admin de mon appli](http://lesjoiesducode.fr/post/132400647502/quand-quelquun-cherche-%C3%A0-ce-que-je-lui-donne-les) - siou plait!!
 * [Quand je découvre les nouvelles demandes du client](http://lesjoiesducode.fr/post/113771728328/quand-je-d%C3%A9couvre-les-nouvelles-demandes-du-client) - J'en crois pas mes yeux.. 

 
