# Refonte du site de pest
* Made by : [Florianccj](https://github.com/FlorianCcj), [Mougne Laura](https://github.com/LauraMgne), Robinson le mec qui a faim
* Duration : 2016-Apr-... to current
* Context : The website of the SLA of gnagnagna, want a more ergonomic website but keeping some structure

## purpose :
- Rendre plus accessible les differentes parties du site
- (facultatif) rendre le site customisable par le common weilth

## Les technos

- html
- css
- javascript
- php
- mysql
- nodejs
- angularj
- Wordpress
- symfony

### Langage de base du web
- html : permet d'ecrire le contenu d'un site ;
- css : permet de mettre en forme le contenu ; 
- javascript (js) : permet de rendre dynamique le site permet a l'utilisitaeur d'interagir avec le site ; 
- php : permet d'interagir avec le serveur et la base de donnée ;
- mysql : permet d'interagir avec la base de donnée (si elle est de type sql).

### CMS
- Wordpress : cms de blog

### framework
- nodejs : framework en javascript orienté vers les applications reseau permetant de gerer le coté client comme le coté serveur d'une application
- angularjs : A part une extension du javascript/jquery je sais pas comment le decrire
- symfony : framework php, modele mvc ayant une grande communauté et des plugin tres simple a ajouter

## Les différentes parties :
- site vitrine
- blog (pour afficher les news)
- wiki (pour toute les questions qu'ont pourrait se poser)
- forum (pour debattre organiser ...)
- calendrier
- archive/galerie photo

### Impératif
 - Le logo des EEDF toujours visible
 - des liens vers le site nationnal

### Le site vitrine
C'est la partie institutionnel, le blabla presentant l'asso, les valeurs, les statuts, ...
Cette partie peut etre faite :
- de a à z à la mano permettant au neophyte d'apprendre le html et le css
- via la fonction des pages de Wordpress

### Le blog
C'est pour donner des nouvelles et de information que ce soit sur l'année ou sur les camps.
L'idée de base etait de le faire sous wordpress amis pour le faire inter-agir avec le reste des composants du site on peut le comme bon nous semble
- permet d'afficher les pages selon des mot clé (camp, week-end, éclé, prépa matos, coincoin, ...)

### wiki 
Le wiki a été précédemment creer via un CMS wiki, je n'ai pas trop d'autre idée pour le moment, potentiellement l'ajouter au squellette du site via une iframe

### forum (pour debattre organiser ...)
Le forum etait initialement fait sous phpbb
Une proposition d'un forum/suivi de proget en systeme kanban a été proposé  https://trello.com/

### calendrier
Gestion des evenements, des participants et chaque utilisateur doit pouvoir afficher le calendrier qui lui plait (conseil de groupe, reponce, ecle, ...)
- permettre l'inscription 
   * des parents voiture
   * des parents course
   * des responses
   * des enfants
   * event (lien wiki vers fiche de route+ date et lieu de la reu de preparation, deadline d'inscription (+menu), lieu et heure de rdv)
   * evenement autre qui ne sont pas du groupe (rassemblement entre autre)
- permettre la synchronisation avec outlook, google, et autre
- imprimer/afficher la liste de pointage (voir permettre le check via smartphone)

### archive/galerie photo
- upload facile (fichier ou dossier)
- organisation par date/activite/photographe
- redimmensionnage et affichage simple et leger
- tellechargement par zip sur autorisation (blocage du telechargement)



//!\\ 1 le but est que ce soit facilement modifiable par quelu'un ayant les identifiants il faut donc une interface permetant de modifier le fond et une pour modifier la forme

//!\\ 2 Le but est la l'interopérabilité du site donc la session du blog doit etre la meme que celle du wiki, du forum, de la galerie photo ... que ce ne soit qu'un seul site quoi

//!\\ 3 google déclasse les dites non smartphone friendly il va donc etre dans les priorités de faire une visualisation pour smartphone (cf. Jj wordpress le fait automatiquement)

### Plus
 - Systeme de newletter permettant d'avoir les nouvelles infos chaque semaines
 - Appli mobile et/ou ordinateur affichant des notifications en cas de changement
 - gestion des menus
	* ingredient
	* quantité
	* prix générique
	* archive de menu
	* rangement par rayon
	* liste de course
 - decma : des comptes, permettant d'acceder au mail, numero, reseau sociaux des autres pour les contacter facilement
 - ajout : permettre au gens de choisir s'ils veulent etre averti si un message privé est arrivé ou nom
 - permettre de choisir si l'on veut partager le numero de tel, mail, autre
 - eonia : une section betise : les responses racontent les betises des enfants (sans donner de nom)
 - bastien : bibliotheque comprennant le lieu de week-end, les doc peda, les doc d inscription, les fiches d'activite
 
 ### Des exemples de site de gestion d'association
 
 - http://garradin.eu/
 - http://noethys.com/index.php/faq/4-sous-quelle-license-est-distribue-noethys 
 - http://idl-mp.com/2013/02/gerer-son-association-sereinement/
et..payant mais chouette / cloud :
http://gerer-mon-association.fr/prix-logiciel-gestion-association