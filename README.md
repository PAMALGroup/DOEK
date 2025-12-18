Données de l'oeuvre

Artiste : Annie Abrahams
Développeur : Jan de Weille
Titre de l'oeuvre : DOEK
Date de création : 1990 - 1993
Classification : Logiciel de création 3D
Site web :
État avant étude : listing papier
Production PAMAL : Second original
Accès PAMAL :
Description

DOEK (signifiant chiffon ou tissu en néerlandais) est un logiciel conçu spécifiquement pour l’artiste dans le cadre de sa recherche plastique. Ce logiciel, permettant à l’artiste de simuler des espaces d’exposition, lui fournissait plusieurs possibilités d’accrochages (il contenait toutes les données et dimensions de ses œuvres).
Il a été conçu par J.R de Weille sur Amiga 500Plus puis 1000 dans les années 1980-90. Cet outil a accompagné l’artiste durant de nombreuses années, témoignant d’une méthodologie de travail et d'une période de création particulière .

Le logiciel permet de créer des scènes, vides au départ, qui vont permettre à l'utilisateur, grâce à la modélisation 3D, de créer une chambre d'exposition où sont stockées plusieurs peintures représentées comme des "boîtes vides" mais avec une position et des dimensions précisées par l'utilisateur. Les objets 3D créés ont une représentation en fil de fer. L'utilisateur utilise sa souris afin de placer des points dans un espace 3D. Chaque point a des coordonnées x, y et z. Deux points peuvent être reliés afin de créer une ligne.
Intérêt du projet
Listing papier de DOEK

Ce logiciel est devenu peu à peu l’outil indispensable d’une démarche de construction artistique dans un univers d’exposition virtuel.
Lors de l’exposition ESCA (1995) il intervient à deux moments clé de l’exposition : pour sa conception (référence toutes les informations pratiques des oeuvres peintes (dimension, système d’accrochage, etc.) ainsi que celles des espaces d’exposition (dimensions, cloisons, fenêtres, etc.) et durant l’exposition (le spectateur pouvait lui-même explorer cet espace potentiel).
Annie Abrahams utilise alors les différents possibles proposé par le logiciel pour créer une autre forme lors d’une temporalité qu’elle appelle la “rechaotisation”. Elle superpose ainsi les possibles pour faire référence à ses tableaux chaotiques et faire renaître sa création : “c’est très important de conclure la mise en ordre ; la construction, avec un acte, qui ramène la totalité à une image plus complexe, à quelque chose de plus proche de (ses) tableaux chaotiques”.
Le logiciel a également servi d’outil pour créer des œuvres physiques, en jouant sur les distorsions de l’espace muséal et les différentes constructions d’accrochages créées pour les expositions. Ses images, étranges et inattendues, “sont intéressantes comme images graphiques classiques, mais elles sont aussi le symbole des possibilités inconnues de la technique. Ces images ne sont pas ‘gratuites’; elles sont toujours basées sur une entité dans la réalité, en l’occurrence sur les tailles physiques de l’espace et les tableaux.”.

Compte tenu des ces précisions, le PAMAL a accepté de travailler sur la création d'un second original de DOEK à partir du seul élément existant encore en possession de l'artiste : le listing papier du programme rédigé en code C.
Environnement matériel et logiciel
AMIGA500plus
AMIGA500plus du PAMAL
Démarrage de l'AMIGA500plus destiné à recevoir le second original

Acquisition
Notre Amiga fut l'objet de quelques recherches sur les sites spécialisés en vente de matériel d'occasion. Il fut acheté sur le site du bon coin auprès d'un particulier avec l'intégralité de sa collection de disquettes ainsi que deux lecteurs de disquette. 
Spécifications techniques
Motorola 68000 (microprocesseur 16/32 bits CISC avec 16 registres sans MMU pour la protection mémoire et la mémoire virtuelle) ;
système d'exploitation par défaut : AmigaOS 1.2 ou 1.3 (ayant un noyau multitâche préemptif) suivant la révision ;
512 Ko de Chip RAM par défaut (mémoires sonore, graphique et logicielle se partageant les mêmes espaces mémoires) ;
limite haute de 16 Mo de mémoire, due aux limitations du MC68000 (adressage mémoire sur 24 bits) ;
chipset OCS  ;
sortie TV 50 Hz (PAL) et 60 Hz (NTSC) par défaut suivant les versions. Mode 50/60 Hz basculant logiciellement dans les révisions suivantes ;
filtre passe-bas audio commutable logiciellement (la diode de l'alimentation s'éteignant (pour les modèles avec led rouge) ou baissant d'intensité quand le filtre est éteint) ;
partage IRQ (comme le bus PCI) ;

le système d'IRQ a 7 niveaux de priorité d'interruptions ; pas de limite dans le nombre d'interruptions ; périphériques gérés par Autoconfig, très similaire à l'ACPI. Les périphériques ne sont pas comptés ou nommés, ils donnent juste la taille et les adresses dont ils ont besoin.

Un lecteur de disquette standard double face/simple densité de 3,5 pouces (3.5") est livré en série, plusieurs peuvent être connectés en externe.

Le lecteur a la particularité d'être complètement pilotable. En effet, l'Amiga peut formater des disquettes de façon complètement libre, le format de base des disquettes sous AmigaDOS étant de 880 Ko, illisible sur PC. Avec un logiciel comme Crossdos, il est cependant possible de lire des disquettes double face/simple densité provenant d'un PC, et formatées par ce même PC.

Deux ports DB-9 pour joystick, souris et crayon optique sont inclus :
un port série RS-232 standard de 25 contacts et
un port parallèle Centronics de 25 contacts.

Le code C

Doek fut écrit en langage C[1] par Jan de Weille.
Copie d'un feuillet du listing
Réalisation du Second Original
De l’analogique au numérique

Dans un premier temps nous avons décidé de le numériser afin de réaliser des copies manipulables. Pour obtenir un résultat satisfaisant nous avons du employer un scanneur A3 car le format d’origine était du A4+, puis retravailler chaque zone imprimée sur les pointillés détachables spécifiques au papier listing.
Premiers tests

Après un court état de l’art concernant les programmes de reconnaissance de caractère ainsi que des logiciels permettant de dicter du texte, nous avons lancé une procédure de test afin de définir la méthode la plus rapide et la plus sure afin d’obtenir le code sous un format numérique. La reconnaissance de caractère montra rapidement ses limites, par exemple en ne pouvant faire la différence entre les 1 et les l ou les ( et le { obtenu avec la police de caractère Courrier, le tout aggravé par la méthode d’impression à aiguilles de l’époque. La dictée directe des lignes de codes se révéla quant à elle encore plus fastidieuse que la simple recopie directe des feuillets de code. C’est donc cette dernière méthode qui a été retenu. Malheureusement n’étant pas familier du langage C, la recopie par nos propres moyens s’avéra rapidement inadaptée de par sa lenteur, augmentée d’un fort risque d’erreur de frappe.
Partenariat avec l'IUT de Arles
Prêt du matériel pour la suite de l'étude sur le site de l'IUT de Arles

La solution fut trouvée en établissant un partenariat avec l’IUT d’Aix-Marseille, site d’Arles. Un groupe de quatre étudiants de licence professionnelle système informatique et logiciel fut donc associé au projet avec un enseignant tuteur, Éric Remy. Les étudiants saisirent l'intégralité du code C, à partir des copies, et effectuèrent la compilation sur Amiga 500 avec lorsque c'était possible l'intégration des fonctions d'origines. Pour des raisons pratiques (rapidité et stabilité) ils travaillèrent sur un émulateur d’Amiga (FS-UAE). En mai 2015, le logiciel DOEK était réactivé sur un Amiga 500, certaines parties du code restant à corriger, des fonctionnalités incomplètes entraînant un blocage de l'ordinateur.

En parallèle, une seconde version de DOEK fut proposée, en ligne et utilisable via un navigateur. Le tout conçu en Javascript avec l'intégration de la police spécifique à l'Amiga. Aujourd'hui cette version en ligne présente un menu et quelques fonctionnalités réduites mais encore beaucoup de lacunes, tant sur le plan esthétique que technique.

Un site Internet a été créé contenant la description complète du projet accompagné d’une documentation exhaustive.

Le site du projet développé par les étudiants de l'IUT
Exposition du second original
Vue générale de la table réunissant les éléments produits lors de l'étude

DOEK a été exposé lors de l'exposition Une Archéologie des médias organisée à Seconde Nature du 20/05/2015 au 28/06/2015.
Notes

https://fr.wikipedia.org/wiki/C_(langage)
