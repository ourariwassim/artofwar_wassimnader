> ***<u>Art of War :</u>***
>
> ***<u>Projet choisi par : </u>*** Nader BEN GHACHEM et Wassim OURARI
>
> ***<u>Sujet :</u>*** Jeu de conquête au Tour par tour (Turn Based
> Strategy)
>
> ***<u>Date :</u>*** 06/04/2024
>
> ***<u>Présentation :</u>***
>
> ***Art of War*** se veut être une introduction ludique et facile à
> prendre en main aux jeux de stratégie militaire au tour par tour.
> Notre objectif est de produire un jeu de type TBS ( turn based
> strategy ) simple , s’inspirant des références du genre ( Par exemple,
> le fameux jeu de stratégie Risk) tout en ayant une atmosphère et des
> thèmes s’ancrant dans des temporalités plus réalistes.
>
> ***<u>Principes du jeu :</u>***
>
> Art of War permettra au(x) joueur(s) de se plonger dans différentes
> cartes issues de différentes époques dans des conflits au tour par
> tour contre l’IA ou jusqu’à contre 3 autres joueurs en local ou en
> ligne. Les joueurs ont pour objectif de former des « *pions »* , pour
> conquérir des « *provinces »* pour obtenir de *« l’or ».* Former des
> troupes nécessite de l’or , obtenir de l’or nécessite de conquérir des
> provinces ou d’occuper celles-ci au début de son tour, sachant que
> chaque province ne fournit pas la même quantité d’or a l’envahisseur
> et que chaque province dispose d’un type de terrain ( Plaine ,
> Montagne , terrain vague) qui modifie les dégâts des types d’unités (
> « bonus » ou «malus ») : Cela permet donc de doter Art of War d’un
> aspect stratégique ou le déplacement et le bon équilibre du type de
> pions – Un pion pouvant être un tireur , un milicien ou un guerrier –
> prime parfois sur le nombre d’unités. Enfin, es pions produits dans la
> même province s’accumulent mais attention : Le prix de formation
> augmente !
>
> ***<u>Pourquoi avoir choisi ce sujet ?</u>***
>
> Notre choix de sujet a été porté par notre intérêt et notre expérience
> des jeux de guerre tactiques, mais aussi, notre passion pour
> l’Histoire et, par la même occasion, notre envie de faire découvrir
> certains événements historiques et permettre aux joueurs de s’immerger
> dans ces derniers, quitte à changer le cours de l’histoire. De plus,
> ce projet nous permettra de mettre en pratique nos acquis en matière
> de réalisation de projets et de programmation.
>
> ***<u>Acteurs :</u>***
>
> <u>-J</u>oueur Humain : Joueur contrôlé par un humain , qui a accès a
> toutes les fonctionnalités du jeu
>
> -Joueur IA : L’IA favorise la tactique ( court terme) et est défensive
> ( attaque rarement en premier)
>
> ***<u>Notions de base/Contraintes :</u>***
>
> L’IA doit avoir un esprit tactique satisfaisant. 

>Interface simple à consulter et à comprendre

>Batailles stratégiques Joueur vs Joueur ou Joueur vs AI pour la
  > capture de provinces

> Instaurer un système de gestion des relations diplomatiques

>Instaurer un système de gain et de dépense de la ressource en or et
  > favoriser un style de jeu dynamique

> Permettre la gestion et la production stratégique de troupes

> Le joueur doit pouvoir s’authentifier à son compte pour. retrouver sa
  > progression

> ***<u>Spécifications du Projet :</u>***
>
> ***Fonctionnalités (Point de Vue utilisateur) :***
>
> ***-Menu Principal :***

> *S’authentifier*: Utiliser un mail et un mot de passe.*

> *Configurer les paramètres audios* : Baisser ou augmenter le volume
  du jeu

> *Lancer une partie * Ouvre l’interface de paramétrage de parties
  > pour préparer celle-ci.

>*Configurer les paramètres de partie :* Paramétrer les conditions
  > de victoire : Joueur contre Joueur ou Joueur contre Machine ,
  > Utiliser une horloge ou un nombre de points maximum, local ou en
  > ligne .*

> *Options*

> *Consulter les statistiques d’un joueur ou de l’IA :* Statistiques
  > de capture : Nombre de provinces capturées, nombre de provinces
  > perdues, Nombre de province contrôlées et Statistiques de l’armée :
  > Nombre de soldats en vie, nombre de soldats perdus, Nombre actuel de
  > soldats*

> *Consulter les relations avec les autres joueurs et l’IA *: Permet
  > de visualiser l’état actuel des relations avec les autres joueurs
  > (Paix, En Guerre, Cessez-le-feu)*

> *Envoyer une demande de Cessez-le-Feu* : Permet d’envoyer une
  > demande de cessez-le-feu a un joueur ennemi : Si le joueur est une
  > IA, il y a 50% de chance qu’il accepte cette demande et la
  > respectera jusqu’à ce que le joueur Humain reprenne la guerre.*

> *Fermer Options* : Permet de retourner sur la Carte du jeu*

> *Abandonner la partie* : Retourner au menu de jeu.*

> *Exporter les statistiques de la partie* : Permet d’enregistrer un
  > fichier contenant les statistiques de la partie pour d’éventuelles
  > analyses de performance.*

> *Consulter l’aide *: Permet d’avoir accès a une liste de conseils
  > et d’indications.*

> *-Carte du jeu :*

> *Passer le tour :* Permet de passer son tour de jeu : S’exécute
  > automatiquement après la prise d’une province/déplacement d’une
  > unité.

> *Sélectionner une province :* Permet de consulter les armées
  > présentes dans la province, l’or obtenu lors de la conquête de la
  > province, le joueur qui la possède et les icones de fabrication de
  > troupes*

> *Sélectionner une unité :* Permet de consulter l’unité sélectionnée
  > pour pouvoir la déplacer*

> *Former un pion :* Se fait après avoir sélectionné une province
  > conquise, un pion selon son type coûtera X quantité d’or.*

> *Déplacer une unité :* Après avoir cliqué sur un pion, le joueur
  > pourra choisir une province ou l’envoyer, à condition que celle-ci
  > soit une province voisine a sa province de déploiement actuelle*

> *Ouvrir l’Interface Options :* Permet d’ouvrir l’interface des
  > Options.*

> *Affichage du logiciel :*

> *Annoncer une déclaration de guerre* : Lorsque le joueur attaque un
  > ennemi ou se fait attaquer*

> *Annoncer une fin de partie :* Lorsqu’une condition de fin de
  > partie est valide*

> *Annoncer le début de tour* : Le joueur est averti que son tour a
  > commencé et obtient une quantité d’or qui dépend du nombre de
  > provinces occupées.*

>*Annoncer la prise/perte d’une province* : Lorsqu’une province est
  > capturée à la suite d’une bataille*

  >*Annoncer la perte d’une unité* : Indique le lieu et l’unité
  > perdue*

> *Annoncer au joueur qu’il n’a pas les moyens de produire une
   unité : Lorsque le joueur clique sur icone de fabrication d’unité
   mais n’a pas l’or requis pour la fabriquer.*

> ***Diagrammes de cas d’utilisation:***
>
> ![image1](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983343/b26b06bc-8da5-48a8-b2aa-c9249d1c9374)

>
> **Priorités des cas d’utilisation :**
>
> **Haute priorité** :

> **Gérer les Éléments Stratégiques (gameplay):**

<!-- -->

> interagir et de prendre des décisions stratégiques pour influencer le
  > déroulement du jeu, en gérant divers éléments tels que les factions,
  > les territoires et les ressources disponibles.

<!-- -->

> **Récupérer les données à partir d'une API REST :**

  > la récupération des informations sur les territoires disponibles,
    > les ressources disponibles, les unités de jeu, etc., à partir d'un
    > serveur centralisé.

> **Analyser les Performances :**

  > Les joueurs pourraient consulter leurs statistiques personnelles,
    > telles que le nombre de territoires conquis,les ressources
    > accumulées, les unités déployées, etc.

- **Authentification :**

  - L'authentification est cruciale pour assurer la sécurité des comptes
    > des joueurs et garantir un accès sécurisé aux fonctionnalités du
    > jeu, notamment la sauvegarde des  
    > progrès et la gestion des données personnelles.

> **Moyenne priorité :**

> **Collecter les données :**

  > Cette fonctionnalité pourrait impliquer la collecte de données sur
    > les actions des joueurs, telles que les mouvements sur la carte,
    > les interactions avec d'autres joueurs ou factions, etc.

> **Gérer les Comptes utilisateurs :**

  > Permettre aux joueurs de créer et de gérer leurs profils et comptes
    > utilisateurs, y compris la personnalisation des paramètres, la
    > gestion des amis, etc.

> **Basse priorité :**

> **Gérer des tableaux de bord :**

  > Permettre aux joueurs de personnaliser leurs tableaux de bord,
    > d'afficher des informations spécifiques ou des indicateurs de
    > performance.

> **Export :**

  > Les joueurs pourraient avoir la possibilité d'exporter des rapports
    > détaillés sur leur performance, leurs réalisations, ou d'autres
    > données pertinentes pour analyse ou partage.

![image2](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983343/b4a9b18c-e32c-4fc1-b332-e8f36a9b231c)
![image3](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983343/f64cf406-ad95-49c3-9411-fa1f36fea9c8)


 -***Diagramme de sequence pour cas Authentification :***
![image](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983405/1a9a5ee1-8f0b-462c-9a07-16ad78bc9438)

 -***Diagramme de sequence pour cas AnalysePerformance :***
![image](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983405/3b01e895-1ba9-44c7-bab6-19e75748951d)

 -***Diagramme de sequence pour cas Cessez-le-feu :***
![image](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983405/db9aef6d-f3b2-4db9-8e9c-437cfc14cc49)

- ***<u>Diagramme de Classe raffiné :</u>***

![classDiagramme2](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983405/e59b6067-9f2b-475f-838b-c8773b12c717)


- ***Diagramme de machine a etat (authentification):***
- 
![image](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983343/b81618a2-ecf9-4c97-8742-9fe2caec40eb)


- **Diagramme de machine a etat (consulter statistiques):**

![image](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983343/12789ec7-7b0a-4288-ac04-c2d8e39173af)


**Langage propositionnelle de classes statistiques::**
>((consultable)^ (nombre_provinces _actuelles != null) ^(nombre_provinces _acquises != null)
>^(nombre_provinces _perdues != null )
>^(nombre_soldats_actuel != null)
>^(Nombre_soldats_perdus != null))
>=>consult
>![c1](https://github.com/ourariwassim/artofwar_wassimnader/assets/162983405/cdc9d9ba-c190-44e6-9677-17767b4d12a6)


