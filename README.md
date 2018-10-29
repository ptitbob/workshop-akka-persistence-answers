# Akka persistence sans les moufles

![](./public/images/unicorns.jpg)


### Pré requis

* `sbt run` à la racine du projet  
* docker  + docker-compose installé + `docker-compose up`  à la racine du projet  
* Accès pgAdmin : http://localhost:5050
    * login : pgadmin4@pgadmin.org - password : admin
    * Au premier lancement, enregitrer la base
        * clic droit sur serveur --> create / server
            * Name : ce que vous voulez, workshop par exemple
            * connection : 
                * host : postgres
                * username : docker
                * password : docker
                * save password : true

*Si vous voulez utiliser votre propre client PostGreSQL, commentez les lignes du docker-compose concernant pgAdmin, cela vous sauvegardera des ressources ;)*

Les tables nécessaires au workshop seront automatiquement créées lors du `docker-compose up`


Nous allons réaliser lors de ce workshop, un trello eventsourcé : 

![](./public/images/trello-event-source.png)

[Workshop](1-workshop.md)

