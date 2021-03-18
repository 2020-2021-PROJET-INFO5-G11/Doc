
<center> <h1>Réseau social d'organisation de sorties</h1> 
 <h1>Osons sortir</h1></center>



<br>
<br>
<br>
<br>
<br>

 
 <center> <h2>Table des matières </h2> </center>
<br>
<br>

**1. [Introduction](#introduction)**  
**3. [Rappel du sujet](#Rappel_du_sujet)**  
**4. [Cahier des charges](#Cahier_des_charges)**  
**5. [Technologies employées](#Technologies_employées)**  
**6. [Architecture technique](#Architecture_technique)**  
**7. [Réalisations techniques](#Réalisations_techniques)**  
**8. [Gestion de projet](#Gestion_de_projet)**  
    7.1. [Méthode](#Méthode)  
    7.2. [Planning prévisionnel et effectif](Planning_prévisionnel_et_effectif)  
    7.3. [Rôles des membres](Rôles_et_membres)  
    7.4. [Gestion des risques](Gestion_des_risques)  
**9.  [Outils](#Outils)**  
**10. [Métriques logiciels](#Métriques_logiciels)**  
**11. [Conclusion](#Conclusion)**  
**12. [Glossaire](#Glossaire)**  
**13. [Bibliographie](#Bibliographie)**  

<br>
<br>
<br>
<br>
<br>

## Introduction <a name="introduction"></a>
Le projet de fin d'étude est l'occasion idéale pour nous étudiants de confirmer nos compétences techniques et d'apprendre à être rigoureux sur les méthodologies de gestion de projet. Cela permet aussi de se rassurer et de gagner en confiance avant le début.

## Rappel du sujet <a name="Rappel_du_sujet"></a>
Ce projet a pour but de créer une application web/mobile de proposition/organisation de sorties et activités sociales. 
Nous n'avons avec aucune base de départ et un choix de technologie partiellement libre. Nous avons eu le choix de la technologie utilisée pour le front end, mais les technologies du back end nous ont été imposées.
L'objectif du projet n'est pas d'avoir une version finale et déployable de l'application, mais plutôt d'avoir une base réutilisable, et de spécifier une première version de l'API REST.

L'application se doit d'être open source.

## Cahier des charges <a name="Cahier_des_charge"></a>
Nous avons créé notre propre cahier des charges basé sur des user stories. Ces user story ont pour but de simuler l'utilisation de l'application par une personne qui n'existe pas, de manière à prédire les éventuelles actions qu'il pourrait faire afin de savoir quelles fonctionnalités seraient intéressantes pour notre application. Ensuite nous discutons entre nous de la faisabilité et de la pertinence de ces fonctionnalités. Puis enfin nous avons consulté notre porteur pour valider avec lui une liste de fonctionnalités à développer.
De cette méthodologie a découlé la liste des fonctionnalités suivantes, qui nous a servi de fil conducteur tout le long de la réalisation de ce projet.  

![](https://i.imgur.com/G202kJ5.jpg)


## Technologies employées <a name="Technologies_employées"></a>
En ce qui concerne les technologies employées, nous avons tout de suite pu discuter avec le porteur de notre projet afin de déterminer les différents langages de programmation et technologies à utiliser.  
En effet, la durée du projet n'étant que d'un mois, il était nécessaire que le porteur puisse reprendre le code de l'application afin de poursuivre son développement.  
#### Backend
**Flask**
Nous avons donc utilisé Flask qui est un framework de développement web en Python et qui nous a permis de créer assez facilement notre application.  
Cette technologie nous a donc permis de réaliser toute la structure du Backend, que ce soit la création de l'API ou la génération de notre base de données.  
Étant donné que nous n'avions jamais utilisé Flask auparavant, nous avons eu beaucoup de mal à établir la structure de notre code côté backend, mais nous avons tout de même su prendre en main les différentes fonctionnalités proposées par ce framework.

**SqlAlchemy**
SqlAlchemy (module de Flask) est un toolkit open source SQL et un mapping objet-relationnel écrit en Python. C'est ce qui relie notre application à notre base de données.  

#### Frontend
**VueJS**
Vue.js, est un framework JavaScript open-source utilisé pour construire des interfaces utilisateur et des single page application ce qui nous confortait donc dans notre choix puisque le porteur du projet souhaitait que notre application soit une SAP.

## Architecture technique <a name="Architecture_technique"></a>

Pour ce projet, nous nous sommes tournés vers une architecture client-serveur. Ainsi, la base de données ainsi que les fonctions sont hébergées sur un serveur, et chaque client a son interface dédiée.  
L'interface de notre application doit pouvoir récupérer les données depuis la base de données. Cela se fait via des requêtes API qui sont alors traitées et permettent donc de récupérer les informations demandées qui seront ensuite affichées sur notre interface.

## Réalisations techniques <a name="Réalisations_techniques"></a>
### Backend
* Développement de l'API
* Création de la base de données
* Requêtes
* Réalisation de tests
* Sécurité : mot de passes cryptés dans la base de données  

<br>

![](https://i.imgur.com/a9Hg3rd.png)


### Frontend
#### Fonctionnalités
* Inscription
* Création, modification et suppression de groupes et de sorties
* Inscription aux sorties et adhésion aux groupes
* Visualisation des sorties à venir et de l’historique des sorties
* Système d’envoi d’invitations pour rejoindre un groupe
* Recherche et filtrage des sorties par catégorie, nom ou ID
* Réalisation d’un header, d’une navbar et d’un footer  

<br>

![](https://i.imgur.com/uHuKg9s.png)


## Gestion de projet <a name="Gestion_de_projet"></a>

### Méthode <a name="Méthode"></a>
Pour ce projet, nous avons choisi de travailler en mode agile, c'est à dire :
+ Définir les fonctionnalités de notre application grâce à des scénarios d'utilisation
+ Répartir la progression du projet en plusieurs sprints
+ Créer des issue pour chaque problème atomique
+ Faire des daily meetings afin de résumer le travail de la veille et de répartir les issue

![](https://i.imgur.com/og4bxK3.png)



### Planning prévisionnel et effectif <a name="Planning_prévisionnel_et_effectif"></a>


![](https://i.imgur.com/MMhqY9q.png)



### Rôles des membres <a name="Rôles_des_membres"></a>

**Rim El Jraidi**, *Chef de projet, développeuse full stack, tests backend*, était chargée de superviser le projet en s'assurant que le groupe avance bien et qu'il n'y ait pas de soucis pour personne. Elle a participé principalement au développement de fonctionnalités du backend mais aussi du frontend. Cette pluridisciplinarité lui a permis d'être réactive sur la correction des bug et donc d'aider tous les membres du groupe si besoin.

**Maxime Vernet**, *Scrum master et développeur front-end*, s'est occupé d'animer les Daily Meetings ainsi que les rétrospective en fin de Sprint. Il a réalisé du développement sur l'interface frontend mais s'est intéressé au backend en profondeur pour pouvoir mieux expliquer ses besoins aux développeurs backend. Il a également rédigé en grande partie la documentation technique destinée aux développeurs qui reprendront le projet dans le futur.

**Idriss Sajide**, *Développeur front-end*, a développé des fonctionnalités du frontend, en collaboration avec Maxime pour une montée en compétence plus efficace.

**Gabriel Manissadjian**, *Développeur back-end*, s'est occupé principalement de la structure du serveur, ainsi que de l'organisation de la base de données. Il 'est aussi occupé de l'intégration des modules de flask nécéssaire à certaines fonctionnalités, comme l'authentification.

Nous avons tous été responsable du Git, c'est à dire que nous avons tous effectué des pull request ainsi que des merge. Nous avons décidé de ne pas donner cette responsabilité à un seul membre du groupe, comme ça a pu l'être pour certains d'entre nous pour le projet d'Ecom, car nous voulions nous assurer d'avoir une montée en compétence homogène sur cet outil de gestion de projet primordial pour notre futur vie professionnelle.

### Gestion des risques <a name="Gestion_des_risques"></a>
Comme expliqué ci-dessus, nous avons tout de suite décidé qu'il était nécessaire de constituer deux binômes différents, chacun se composant d'un développeur back et d'un développeur front afin de faciliter au maximum la liaison entre notre interface et notre base de données. De ce fait, nous avons, également, pu minimiser les conséquences de possibles absentéismes puisqu'il y avait toujours au moins une personne pouvant gérer le côté back ou front de l'application.  
L'utilisation de Github nous a également permis d'éviter toute perte de code utile mais aussi d'avoir une sauvegarde permanente de notre avancée en cas d'erreur.

## Outils <a name="Outils"></a>
Afin de faciliter notre développement, nous avons utilisé plusieurs logiciels :
+ **Github**, qui nous a permis de partager les documents, le code, de faciliter la communication interne et de garder des sauvegardes de notre code en cas d'erreur
+  **Discord**, qui nous a permis de communiquer lors du travail en distanciel
+  **Balsamiq**, qui nous a servi lors de la réalisation de l'IHM abstraite
+  **Figma**, avec lequel nous avons réalisé les maquettes de notre projet

## Métriques logiciels <a name="Métriques_logiciels"></a>
Afin d'estimer le coût du projet, nous avons utilisé la méthode COCOMO.

Pour celle-ci, nous devons tout d'abord déterminer le niveau de complexité de notre projet.
Puisque notre application est assez petite, nous avons considéré que c'était une application organique.
Nous devons ensuite compter le nombre de lignes de notre projet.
Ainsi, la partie serveur compte 2370 lignes, et la partie client en compte 4130, pour un total de 6500 lignes.

La méthode COCOMO nous donne le calcul suivant en fonction de nos paramètres :
Effort = 2.4* (6500/1000)<sup>1,05</sup> = 17.1 mois-homme

Sachant qu’un développeur débutant en France a un salaire de 3100€ brut/mois, on obtient un coût de 53 010€.

On y ajoute en tant que charge les coûts d'abonnement aux transports en commun ainsi que ceux des déplacements pour environ 150€

Cela nous fait un coût total d'environ 53 200€ pour le développement de l'application.

## Conclusion <a name="Conclusion"></a>
Ce projet a été très intéressant pour plusieurs raisons. D'abord, le fait d'avoir une grande liberté sur le choix des technologies et les fonctionnalités à développer nous a rendu autonome. Cela nous a encouragés à faire des recherches et à nous renseigner sur des choses nouvelles afin de justifier nos choix.
L'autonomie dont nous avons fait preuve a renforcé notre confiance en nous et nous a préparé pour notre stage et notre futur vie professionnelle.
Ce projet nous a également permis de nous familiariser avec des méthodes de gestion de projet nouvelles (poker planning).

Nous avons cependant le regret de ne pas avoir eu plus de temps pour aller plus loin au niveau du développement des fonctionnalités de l'application.


## Bibliographie <a name="Bibliographie"></a>
**Documentation Flask :** [Flask](https://flask.palletsprojects.com/en/1.1.x/). 

**Documentation SqlAlchemy :** [SqlAlchemy](https://docs.sqlalchemy.org/en/14/). 

**Documentation Pytest :** [Pytest](https://docs.pytest.org/en/stable/contents.html). 

**Documentation VueJS :** [VueJS](https://fr.vuejs.org/v2/guide/). 





