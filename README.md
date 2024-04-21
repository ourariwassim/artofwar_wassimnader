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
> *-L’IA doit avoir un esprit tactique satisfaisant. -*

- Interface simple à consulter et à comprendre

- Batailles stratégiques Joueur vs Joueur ou Joueur vs AI pour la
  > capture de provinces

- Instaurer un système de gestion des relations diplomatiques

- Instaurer un système de gain et de dépense de la ressource en or et
  > favoriser un style de jeu dynamique

- Permettre la gestion et la production stratégique de troupes

- Le joueur doit pouvoir s’authentifier à son compte pour. retrouver sa
  > progression

> ***<u>Spécifications du Projet :</u>***
>
> ***Fonctionnalités (Point de Vue utilisateur) :***
>
> ***-Menu Principal :***

- ***S’authentifier **: Utiliser un mail et un mot de passe.*

- ***Configurer les paramètres audios** : Baisser ou augmenter le volume
  > du jeu*

- ***Lancer une partie **:* Ouvre l’interface de paramétrage de parties
  > pour préparer celle-ci.

- ***Configurer les paramètres de partie :** Paramétrer les conditions
  > de victoire : Joueur contre Joueur ou Joueur contre Machine ,
  > Utiliser une horloge ou un nombre de points maximum, local ou en
  > ligne .*

> ***-Options***

- ***Consulter les statistiques d’un joueur ou de l’IA :** Statistiques
  > de capture : Nombre de provinces capturées, nombre de provinces
  > perdues, Nombre de province contrôlées et Statistiques de l’armée :
  > Nombre de soldats en vie, nombre de soldats perdus, Nombre actuel de
  > soldats*

- ***Consulter les relations avec les autres joueurs et l’IA **: Permet
  > de visualiser l’état actuel des relations avec les autres joueurs
  > (Paix, En Guerre, Cessez-le-feu)*

- ***Envoyer une demande de Cessez-le-Feu** : Permet d’envoyer une
  > demande de cessez-le-feu a un joueur ennemi : Si le joueur est une
  > IA, il y a 50% de chance qu’il accepte cette demande et la
  > respectera jusqu’à ce que le joueur Humain reprenne la guerre.*

- ***Fermer Options** : Permet de retourner sur la Carte du jeu*

- ***Abandonner la partie** : Retourner au menu de jeu.*

- ***Exporter les statistiques de la partie** : Permet d’enregistrer un
  > fichier contenant les statistiques de la partie pour d’éventuelles
  > analyses de performance.*

- ***Consulter l’aide **: Permet d’avoir accès a une liste de conseils
  > et d’indications.*

> ***-Carte du jeu :***

- **Passer le tour :** Permet de passer son tour de jeu : S’exécute
  > automatiquement après la prise d’une province/déplacement d’une
  > unité.

- ***Sélectionner une province :** Permet de consulter les armées
  > présentes dans la province, l’or obtenu lors de la conquête de la
  > province, le joueur qui la possède et les icones de fabrication de
  > troupes*

- ***Sélectionner une unité :** Permet de consulter l’unité sélectionnée
  > pour pouvoir la déplacer*

- ***Former un pion :** Se fait après avoir sélectionné une province
  > conquise, un pion selon son type coûtera X quantité d’or.*

- ***Déplacer une unité :** Après avoir cliqué sur un pion, le joueur
  > pourra choisir une province ou l’envoyer, à condition que celle-ci
  > soit une province voisine a sa province de déploiement actuelle*

- ***Ouvrir l’Interface Options :** Permet d’ouvrir l’interface des
  > Options.*

> ***-Affichage du logiciel :***

- ***Annoncer une déclaration de guerre** : Lorsque le joueur attaque un
  > ennemi ou se fait attaquer*

- ***Annoncer une fin de partie :** Lorsqu’une condition de fin de
  > partie est valide*

- ***Annoncer le début de tour** : Le joueur est averti que son tour a
  > commencé et obtient une quantité d’or qui dépend du nombre de
  > provinces occupées.*

- ***Annoncer la prise/perte d’une province** : Lorsqu’une province est
  > capturée à la suite d’une bataille*

- ***Annoncer la perte d’une unité** : Indique le lieu et l’unité
  > perdue*

- ***Annoncer au joueur qu’il n’a pas les moyens de produire une
  > unité :** Lorsque le joueur clique sur icone de fabrication d’unité
  > mais n’a pas l’or requis pour la fabriquer.*

> ***Diagrammes de cas d’utilisation:***
>
> <img src="media/image1.jpg" style="width:5.55787in;height:9.0625in" />
>
> **Priorités des cas d’utilisation :**
>
> **Haute priorité** :

- **Gérer les Éléments Stratégiques (gameplay):**

<!-- -->

- interagir et de prendre des décisions stratégiques pour influencer le
  > déroulement du jeu, en gérant divers éléments tels que les factions,
  > les territoires et les ressources disponibles.

<!-- -->

- **Récupérer les données à partir d'une API REST :**

  - la récupération des informations sur les territoires disponibles,
    > les ressources disponibles, les unités de jeu, etc., à partir d'un
    > serveur centralisé.

- **Analyser les Performances :**

  - Les joueurs pourraient consulter leurs statistiques personnelles,
    > telles que le nombre de territoires conquis,les ressources
    > accumulées, les unités déployées, etc.

- **Authentification :**

  - L'authentification est cruciale pour assurer la sécurité des comptes
    > des joueurs et garantir un accès sécurisé aux fonctionnalités du
    > jeu, notamment la sauvegarde des  
    > progrès et la gestion des données personnelles.

> **Moyenne priorité :**

- **Collecter les données :**

  - Cette fonctionnalité pourrait impliquer la collecte de données sur
    > les actions des joueurs, telles que les mouvements sur la carte,
    > les interactions avec d'autres joueurs ou factions, etc.

- **Gérer les Comptes utilisateurs :**

  - Permettre aux joueurs de créer et de gérer leurs profils et comptes
    > utilisateurs, y compris la personnalisation des paramètres, la
    > gestion des amis, etc.

> **Basse priorité :**

- **Gérer des tableaux de bord :**

  - Permettre aux joueurs de personnaliser leurs tableaux de bord,
    > d'afficher des informations spécifiques ou des indicateurs de
    > performance.

- **Export :**

  - Les joueurs pourraient avoir la possibilité d'exporter des rapports
    > détaillés sur leur performance, leurs réalisations, ou d'autres
    > données pertinentes pour analyse ou partage.

\-

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 64%" />
</colgroup>
<thead>
<tr class="header">
<th>Titre</th>
<th>Analyser les Performances</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Acteur</td>
<td>Joueur</td>
</tr>
<tr class="even">
<td>Description</td>
<td>Permet aux joueurs de consulter leurs statistiques personnelles,
telles que le nombre de territoires conquis, les ressources accumulées,
les unités déployées, etc.</td>
</tr>
<tr class="odd">
<td>Précondition</td>
<td>Authentification</td>
</tr>
<tr class="even">
<td>Postcondition</td>
<td>Statistiques affichées</td>
</tr>
<tr class="odd">
<td>Scénario nominal</td>
<td><ol type="1">
<li><p>Le joueur accède à la section "Analyser les Performances" dans le
menu du jeu.</p></li>
<li><p>Le système affiche les statistiques personnelles du joueur, y
compris le nombre de territoires conquis, les ressources accumulées, les
unités déployées, etc.</p></li>
<li><p>Le joueur peut naviguer et filtrer les statistiques selon ses
préférences.</p></li>
<li><p>Le système met à jour les statistiques en temps réel pour
refléter les changements dans le jeu.</p></li>
<li><p>Le joueur utilise ces informations pour suivre sa progression et
prendre des décisions stratégiques informées.</p></li>
</ol></td>
</tr>
<tr class="even">
<td>Scénario d’exception</td>
<td><ol type="1">
<li><p>Si le joueur n'a pas encore de statistiques disponibles (par
exemple, s'il n'a pas encore commencé à jouer), le système affiche un
message approprié informant que les statistiques seront disponibles une
fois qu'il aura joué.</p></li>
<li><p>Si le joueur rencontre des problèmes pour accéder à ses
statistiques, le système affiche un message d'erreur et propose des
solutions de dépannage.</p></li>
</ol></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 33%" />
<col style="width: 18%" />
<col style="width: 13%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"></th>
<th>1</th>
<th>2</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Précondition</td>
<td>Authentification</td>
<td>F</td>
<td>T</td>
</tr>
<tr class="even">
<td>Postcondition</td>
<td>Statistiques affichées</td>
<td>F</td>
<td>T</td>
</tr>
<tr class="odd">
<td colspan="2">Nombre de jeux de Tests</td>
<td>1</td>
<td>1</td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 64%" />
</colgroup>
<thead>
<tr class="header">
<th>Titre</th>
<th>Récupérer les données depuis une API REST</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Acteur</td>
<td>Joueur</td>
</tr>
<tr class="even">
<td>Description</td>
<td>Permet de récupérer des informations sur les territoires
disponibles, les ressources disponibles, les unités de jeu, etc., à
partir d'un serveur centralisé via une API REST.</td>
</tr>
<tr class="odd">
<td>Précondition</td>
<td>Authentification</td>
</tr>
<tr class="even">
<td>Postcondition</td>
<td>Données récupérés</td>
</tr>
<tr class="odd">
<td>Scénario nominal</td>
<td><ol type="1">
<li><p>Le joueur accède à une fonctionnalité ou à une interface dans le
jeu pour récupérer les données depuis l'API REST.</p></li>
<li><p>Le système envoie une requête à l'API REST pour obtenir les
informations nécessaires.</p></li>
<li><p>L'API REST retourne les données demandées au système.</p></li>
<li><p>Le système traite les données reçues et les rend disponibles dans
le jeu pour que les joueurs puissent les utiliser.</p></li>
<li><p>Les joueurs peuvent maintenant interagir avec les informations
récupérées dans le monde du jeu, telles que les territoires disponibles,
les ressources, les unités, etc.</p></li>
</ol></td>
</tr>
<tr class="even">
<td>Scénario d’exception</td>
<td><ol type="1">
<li><p>Si la connexion à l'API REST échoue, le système affiche un
message d'erreur indiquant que les données ne peuvent pas être
récupérées pour le moment. Il propose également des solutions de
dépannage.</p></li>
<li><p>Si les données retournées par l'API REST sont incomplètes ou
corrompues, le système affiche un avertissement indiquant que les
informations peuvent être incorrectes et conseille aux joueurs de
réessayer ultérieurement.</p></li>
</ol></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 28%" />
<col style="width: 27%" />
<col style="width: 22%" />
<col style="width: 21%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"></th>
<th>1</th>
<th>2</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Précondition</td>
<td>Authentification</td>
<td>F</td>
<td>T</td>
</tr>
<tr class="even">
<td>Postcondition</td>
<td>Données récupérées</td>
<td>F</td>
<td>T</td>
</tr>
<tr class="odd">
<td colspan="2">Nombre de jeux de Tests</td>
<td>1</td>
<td>1</td>
</tr>
</tbody>
</table>

> **Diagramme de sequence pour cas Authentification:**
>
> <img src="media/image2.png" style="width:4.88542in;height:3.70833in" />
>
> **Diagramme de sequence pour cas AnalysePerformance:**
>
> <img src="media/image3.png" style="width:5.75379in;height:3.375in" />
>
> **Diagramme de sequence pour cas Cessez-le-feu:**
>
> <img src="/media/image5.png" style="width:5.24148in;height:3.34564in" />

- ***<u>Diagramme de Classe raffiné :</u>***

> <img src="/media/image6.png" style="width:5.99792in;height:4.20621in"
> alt="Une image contenant texte, diagramme, Plan, Police Description générée automatiquement" />

- ***Diagramme de machine a etat (authentification):***

> <img src="/media/image7.png" style="width:5.52083in;height:3.48958in" />

- **Diagramme de machine a etat (consulter statistiques):**

> <img src="/media/image8.png" style="width:5.60417in;height:4.83333in" />

![Uploading image.png…]()

![Uploading image.png…]()


![Uploading 3336527b-3824-4ead-8868-0352f74e6b93.jpeg…]()
