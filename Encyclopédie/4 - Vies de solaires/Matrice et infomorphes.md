# Matrice et infomorphes

> *« Il est mort. Disparu. Je l’ai effacé. Comme je le ferais à tous ceux qui nous font du mal. »*
>
> Idle, nevian dans un mauvais jour

SolNet et la matrice sont le grand réseau informatique qui relie les colonies et les solaires. Sur ce réseau, vivent notamment les infomorphes : les IA et les éthérés. Ceux-ci sont des êtres réduits à de simples flux de données et disposant d’instances exécutées sur les serveurs et autres appareils du réseau SolNet. Il s’agit sans doute des êtres de Solaires les plus exotiques pour un habitant du début du siècle. Voici une description de ce formidable réseau, de ses particularités et des informorphes.

>> Ce chapitre offre des informations relativement détaillées sur le fonctionnement de SolNet, de la matrice et sur les infomorphes. Pour autant ces informations ne doivent pas être systématiquement utilisées en jeu sous peine d’apporter une complexité inutile au récit. De façon générale, n’essayez pas de simuler le fonctionnement exact de tout ceci et préférez vous en tenir aux intentions des personnages et aux conséquences des actions.

## SolNet

SolNet est le grand réseau qui couvre le système solaire, c’est en quelque sorte le successeur d’Internet élargi. C’est un réseau entièrement décentralisé capable de construire de façon automatique des caches des données les plus demandées et même d’anticiper certaines demandes.

>> ### Les nœuds SolNet
>>
>> Le réseau SolNet relie des milliards de milliards d’appareils. Ces appareils sont des serveurs, des links, des robots domestiques, des accessoires connectés, etc. Tout ce qui est relié à ce formidable réseau est appelé nœud SolNet.

On distingue plusieurs zones dans le réseau en fonction de la disponibilité des données, caches compris :
* **La zone super-locale** : les données sont placées dans le même lieu physique (colonie, station, vaisseau) et sont accessibles en quelques microsecondes ;
* **La zone locale** : tout ce qui est disponible sur le même astre, les données sont accessibles en quelques dizaines ou centaines de millisecondes ;
* **La zone voisine** : tout ce qui est disponible dans le même système planétaire : les données sont accessibles en plusieurs secondes.
* **La zone étrangère** : tout ce qui est absent des caches des zones précédentes et situé sur d’autres systèmes planétaires. Les données peuvent mettre plusieurs heures pour être récupérées.

Il n’y a plus de moteur de recherche centralisé comme Internet en a connu. À la place, des agents logiciels sautent de nœuds en nœuds et explorent le réseau à la recherche des informations demandées en utilisant les caches de SolNet. Ces agents peuvent parfois mettre plusieurs heures pour retrouver un résultat de la zone étrangère. Les agents de recherche ne peuvent trouver que des données publiques, ce qui suffit à la majorité des utilisateurs et utilisations de SolNet.

## La matrice

Certains utilisateurs ne peuvent se contenter des informations publiques de SolNet, ceux-là utilisent la matrice.

Cette matrice n’est rien d’autre que le réseau SolNet vu sans les couches d’abstraction habituelles. Elle se présente sous la forme brute des nœuds reliés par leurs connexions. Avec les bons logiciels, il est alors possible de détecter les logiciels qui y circulent, d’intercepter des messages – mais pas de les décoder – et même d’attaquer des serveurs.

Pour accéder à la couche bas niveau de SolNet, il est nécessaire d’utiliser des outils et des logiciels adaptés. L’outil central pour les non-infomorphes est la console de décryptage. Cet appareil permet de faire le lien entre le réseau SolNet et les interfaces virtuelles de son utilisateur. Elle sert aussi de zone tampon entre ces deux mondes et protège l’utilisateur d’une éventuelle attaque informatique qui serait sinon directement dirigée sur lui. Il vaut mieux une console détruite qu’un cerveau électronique dans le même état.

De leur côté, les infomorphes sont directement sur la matrice. Ils n’ont donc pas besoin d’une console de décryptage pour y accéder. Cela signifie aussi qu’ils ne bénéficient pas d’une telle protection non plus et qu’ils sont donc en première ligne.

## Explorer la matrice

Une grande partie du travail d’un decker consiste à écouter le réseau et à étudier sa configuration.

Pour explorer la matrice, les deckers partent nécessairement de leur point d’injection : le nœud de leur console, ou celui où ils s’exécutent dans le cadre d’un informorphe. De là, ils peuvent envoyer des messages adressés aux différents systèmes du réseau. Mais généralement, un decker n’a pas envie que quelqu’un puisse aisément associer ses messages à son point d’injection. Aussi, ils installent des relais – des agents logiciels spécialisés – sur les nœuds proches par lesquels ils font passer leurs messages pour faire croire à la destination que leur message provient de ces nœuds-ci.

En avançant de nœuds en nœuds, les deckers constituent ce qu’ils appellent leur « fil d’Ariane ». Ces fils ne sont que rarement linéaires et ressemblent le plus souvent à des labyrinthes avec des culs de sac et des boucles. Tant que ce fil d’Ariane n’est pas coupé par un adversaire, le decker peut opérer comme s’il se trouvait en n’importe quel point de son fil d’Ariane.

En observant les informations de routage des messages sur le réseau, les informations qui indiquent d’où le message est partie et où il doit aller, un decker peut se faire une bonne idée des logiciels et informorphes présent sur le réseau. En restant vigilant, le decker réduit considérablement les chances d’être pris par surprise.

## Guerre électronique

Observer et explorer le réseau ne permet pas d’obtenir les informations sensibles ni de prendre le contrôle d’un appareil. Pour y parvenir, il est nécessaire d’exécuter une attaque sur le nœud concerné.

Tous les nœuds de SolNet sont protégés par des intelligences artificielles dédiées : les glaces. Sans elles, les logiciels de piratages sont capables de trouver une faille dans n’importe quel nœud en quelques secondes. Les glaces analysent les données envoyées et bloquent les requêtes suspectes avec une efficacité surprenante. Particulièrement résilientes et robustes elles sont aussi très difficiles à attaquer directement.

Sans un brise-glace, un autre type d’intelligence artificielle spécialisée, il est pratiquement impossible de forcer une glace. Mais même avec, la situation n’est pas triviale pour autant.

Après avoir localisé sa cible sur la matrice, le decker peut envisager plusieurs approches : attaquer directement la glace ou maquiller des données malicieuses et les envoyer dans le serveur à l’insu de la glace.

La première solution ne prend qu’une fraction de seconde et laisse théoriquement une plus grande fenêtre d’action au pirate ensuite. Malheureusement, les glaces sont capables de détecter une telle attaque et de prévenir qui de droit dans la plupart des cas, ainsi que de commander l'extinction du serveur. Celle situées sur des serveurs militarisés sont mêmes équipées de logiciels d’attaque et de brises glaces et s’avèrent capables de riposter par elles-mêmes si elles ont survécue à l'attaque. En situation d’urgence, ceci reste malgré-tout la meilleure solution.

L’autre possibilité est beaucoup plus longue puisqu’elle demande au brise-glace d’étudier le comportement de la glace pendant de nombreuses minutes, voire des heueres, avant de pouvoir lancer l’attaque. L’attaque en elle-même est alors particulièrement brève, la brèche faite dans la vigilance de la glace ne dure que quelques millisecondes. Ce temps ne permet que l’envoi d’instructions simples : le téléchargement d’une IA ou même d’un persona n’est pas réalisable. Il force même l’attaquant à planifier l’intégralité des instructions à exécuter avant l’attaque.

La première option est ainsi plus offensive, tandis que la seconde correspond mieux à la situation où la discrétion est de mise.

Précisons que la plupart des nœuds d’un réseau sont conçus pour être inspectés par un superviseur, un nœud particulier qui s’assure que le réseau est dans un état convenable. Pour pouvoir effectuer son travail, ce superviseur dispose de certificats qui l’autorisent à passer les glaces du réseau sous sa protection. Si un decker parvient à attaquer le nœud de ce superviseur, il peut alors de servir de ses certificats et prendre de fait le contrôle du réseau concerné sans déclencher ses glaces.

## Affrontements matriciels

Certaines glaces ont la capacité de riposter si elles sont directement attaquées. D’autres systèmes de sécurités, en particulier les superviseurs mais aussi d’autres deckers, peuvent aussi chercher à neutraliser un agent sur la matrice.

La plupart des affrontements matriciels commencent lorsque l’activité d’un pirate s’est fait repérer par un système de sécurité ou un autre decker, le défenseur. Normalement le système déclenché commence par rechercher l’importun, notamment en essayant de remonter son fil d’Ariane. Évidemment en le faisant, il risque de déclencher certains pièges laissés par le pirate qui risque d’être prévenu. D’ordinaire, le défenseur possède encore l’avantage à ce moment, car le pirate n’a pas encore commencé à le rechercher. Mais cet avantage est bien faible, car le défenseur n’a pas eu le temps de déployer un fil d’Ariane complexe.

Au fil de leur progression, les deux camps peuvent couper le fil d’Ariane de l’autre, réduisant considérablement la liberté d’action de son adversaire. Dès que l’un des deux belligérants parvient à atteindre le point d’injection de l’autre, il peut l’attaquer plus directement.

Généralement, l’attaque finale revient à attaquer la glace protégeant la console ou l’infomorphe de l’adversaire et de détruire ce qu’elle protégeait. Si c’était un informorphe, il sera effacé. Si c’est un decker connecté à une console, il est éjecté de la matrice. D’ailleurs, un organique qui se déconnecte brutalement, volontairement ou suite à la destruction de sa console, peut subir un contre-coup important impliquant nausées et désorientation.

>> ### Conséquences des affrontements matriciels
>>
>> Dans solaires l’informatique est directement reliée aux choses réelles : jouer avec les appareils qui entourent les personnages provoque toujours des conséquences. Et les dégâts sur le réseau entraînent des dysfonctionnements hors de la matrice. En bref, avant d’attaquer un serveur, un decker ou une IA devrait toujours vérifier ce qu’il attaque et prendre en compte les conséquences.
>>
>> Pire encore, lors d’un affrontement virtuel, il peut rapidement y avoir des conséquences et des dégâts collatéraux. À la différence des combats physiques, il est permis que de considérer que toutes les armes employées par les deckers sont l’équivalent d’armes lourdes. Un logiciel capable de passer une glace est à même de réduire à néant toute une infrastructure mal protégée et lorsque la grille d’un secteur complet d’une colonie saute, les complications qui suivent sont généralement d’ampleur cataclysmique. N’oublions pas non plus tous les appareils connectés au réseau, comme les recycleurs atmosphériques, les canaux de réalité augmentée, la distribution du courant, les robots de maintenance, etc. Dans les pires cas, même une bombe au plasma n’aurait par un impact aussi important.

## IA et éthérés sur le réseau

Les informoprhes sont des êtres de pure information décrits comme vivant libres sur le réseau. En réalité, ils ne sont pas aussi libres que ça : pour pouvoir s’exécuter, ils ont besoin d’un processeur. Par convention, chaque nœud public de SolNet, en plus d’héberger le cache de données, offre quelques processeurs en libre-service pour permettre l’exécution de nombreux logiciels, notamment les agents de recherche et les êtres dépourvus de corps. C’est l’équivalent des installations pressurisées pour les informorphes.

Certaines zones du cache de SolNet permettent aussi de stocker les sauvegardes. Lorsqu’un infomorphe souhaite enregistrer une sauvegarde dans ce système, il l’y insère avec un agent qui surveille l’éventuel signal de vie de l’IA qui sera capable, s’il reste sans nouvelle pendant un certain temps, de ré-instancier la sauvegarde sur le réseau. Ces zones du cache sont spéciales : construites sur un circuit physique spécial, il n’est pas possible d’en lire ou extraire les données depuis l’extérieur, seul l’agent associé peut le faire. Si un autre infomorphe tente d’y insérer une nouvelle sauvegarde, la précédente, et son agent, seront complètement effacées avant.

Évidemment, ces nœuds ont une capacité limitée et certains peuvent se retrouver surchargés, ralentissant notablement les logiciels exécutés. Certaines attaques informatiques consistent ainsi à lancer un grand nombre de programmes sur ces nœuds pour causer un ralentissement considérable et ainsi prendre un avantage certain sur les infomorphes qui y sont localisés. Il est utile de rappeler qu’abuser de ces nœuds est évidemment illégal et que chaque corporation n’hésite pas à poursuivre et punir les contrevenants.

Les infomorphes sont les êtres les plus mobiles dans le système solaire et ils peuvent se déplacer sur des distances lointaines grâce aux connexions SolNet. Cette méthode de voyage permet littéralement de se déplacer à la vitesse de la lumière. Toutefois, il est nécessaire de demander l’autorisation d’injection ce qui demande une communication aller-retour préliminaire. Ensuite, si le téléversement en lui-même échoue, il faut attendre une communication retour, plus quelques secondes de sécurité, avant de réessayer ou d’abandonner.

>> En pratique, il n’est généralement pas nécessaire de se préoccuper de ces mécanismes qui devraient rester transparents pour le joueur. Tant que le réseau SolNet est accessible, il est généralement plus commode de considérer que l’IA est localisée sur le réseau sans chercher plus de précision. Dans le cas contraire, ou si un affrontement informatique s’engage, il faut évidemment en tenir compte.

>> ### Gérer les infomorphes
>>
>> La gestion des infomorphes peut vite devenir très difficile. N’existant que virtuellement, ils n’ont pas d’impact direct sur le physique et n’interagissent avec les autres personnages que via SolNet et la réalité augmentée, où ils peuvent projeter leur avatar. De l’autre côté, ils peuvent virtuellement se rendre n’importe où à la vitesse de la lumière, littéralement.
>>
>> L’un des principaux écueils est de sous-estimer les difficultés qu’ils ont pour interagir avec le monde physique. S’ils ont facilement accès à tout ce qui est public, ce n’est pas le cas pour le reste s’ils n’en ont pas les certificats appropriés. Dans ce cas, ils ne peuvent interagir qu’au travers d’une attaque informatique. Et c’est un acte qui peut avoir des conséquences importantes.
>>
>> Un infomorphe peut emprunter un corps temporaire depuis une station de téléchargement : il y en a dans tous les spatioports, ainsi que les grandes stations, et leur usage est quelque chose de très courant. Mais l’infomorphe sera limité par les performances de son enveloppe et subira le phénomène d’embodiement. Généralement, il sera bien moins à l’aise que ses compagnons de chair et de métal.
>>
>> Il peut être tentant pour un informorphe de prendre en main toute une enquête et de faire cavalier seul, profitant de sa mobilité pour aller interroger des gens et chercher des données un peu partout. Toutefois, il ne doit pas oublier que si un infomorphe à la capacité de trouver de l’information plus facilement (encore que s’il n’est pas formé au piratage informatique, il ne remplacera certainement pas un decker, même débutant), il n’a pas les capacités d’actions de ses camarades. Par exemple, un informorphe qui se télécharge pour interroger un témoin, ne pourra pas le protéger si des adversaires s’en aperçoivent.
>>
>> N’oubliez pas non plus que la plupart des personnages peuvent aussi se télécharger dans des corps temporaires pour mener une enquête à distance. Ce n’est pas une faculté réservée aux infomorphes.