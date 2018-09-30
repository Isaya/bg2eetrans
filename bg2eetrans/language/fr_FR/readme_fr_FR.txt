Ce mod installe une traduction partielle des textes pour BG2EE à partir des textes récupérés de BG II + ToB (original) et des traductions de BGEE (V2.5) et IWDEE (V2.5) mais également une traduction d'une partie des textes ajoutés dans BG2EE.

Remarque : le mod est basé sur une recherche de correspondance entre les textes en anglais de BG2EE et ceux de BG II + ToB et de BGEE date des versions 2.3 de BG2EE et de BGEE. Par conséquent il ne remplace en français que les textes suffisamment proches en anglais. Lorsque les textes de BG2EE ont trop changé par rapport à BG II + ToB, le mod préfère préserver le texte anglais plutôt que remplacer par une traduction qui pourrait s'avérer fausse, particulièrement pour les aspects techniques du jeu (description des classes, kits, sorts, objets). Une partie de ces textes non récupérés a été traité à la main, soit en confirmant par un humain que le texte original convenait soit en modifiant le texte pour assurer une bonne traduction.

Par ailleurs le mod modifie la liste de langues disponibles dans BG2EE (V2.0 et supérieur) afin d'ajouter le français dans la liste et fournit le fichier de traduction de l'interface du jeu.


Historique
----------
Remarque : la version s'écrit sous la forme X.Y.révision_du_jeu
La révision du jeu est la révision de BG2EE à partir de laquelle l'algorithme de recherche de correspondance de textes avec ceux de ToB et BGEE a été faite ou la dernière pour laquelle les textes ajoutés ou modifiés ont été pris en compte. Ce n'est pas nécessairement la dernière en cours. Cette révision n'a pas d'incidence sur la compatibilité du mod avec une version particulière du jeu.
La conséquence est que les textes ajoutés par Beamdog après la révision indiquée ne sont pas pris en compte et resteront en anglais quoi qu'il arrive. En cas de modification de texte, le mod ne tiendra pas non plus compte du changement. Néanmoins le risque est assez faible qu'il y ait eu des changements remettant en cause la validité du choix de reprendre la traduction d'origine ou de laisser le texte en anglais (pour les textes du jeu original).

V0.1.2030 - 23 décembre 2013
- version non diffusée ayant permis de générer les fichiers dialog.tlk et dialogF.tlk mis à disposition pour les versions 1.2 et ultérieurement 1.3 de BG2EE

V0.2.2064 - 28 mai 2016
- prise en compte de BG2EE V2.x ; ajout de la langue française dans BGEE.lua afin qu'elle soit accessible dans l'écran des options
- ajout du fichier de traduction de l'interface du jeu pour BG2EE V2.x

V0.3.2064
- correction du fichier de traduction de l'interface
- différentiation Windows / Linux et Mac sur la manière de lancer l'installation des textes (retour de zelurker)
- complément de détection d'erreur pour signaler l'utilisation d'une version insuffisante de WeiDU pour BG2EE V2.x

v0.4.67.3 - 18 décembre 2016
- récupération d'une centaine de traductions depuis BGEE V2.3.67.3
- ajout de notes sur la version française (idée de zelurker)
- nombreuses corrections de correspondances de textes grâce aux efforts de dricks, zelurker, Luren et Freddy_Gwendo
  * des correspondances inexactes ont été corrigées
  * des correspondances nouvelles ont été vérifiées, ce qui augmente le nombre de textes traduits
  * restauration de voix et de sons ayant disparu ou incorrects (notamment sur des personnages recrutables)

v0.5.67.3 - 8 janvier 2017
- modification de la récupération de texte à partir de BGEE pour qu'elle ne prenne pas le pas sur de meilleurs textes trouvés dans ToB
- nombreuses améliorations et corrections diverses de Freddy_Gwendo
  * respect de l'affichage avec ou sans majuscule initiale pour les noms de kits
  * corrections de mots, uniformisation avec les EE (ensorceleur, cavalier), retraits des "Utilisable par" restants
  * uniformisation de l'affichage des bonus des armes +n (sans espace)
  * des correspondances nouvelles ont été vérifiées, ce qui augmente le nombre de textes traduits, en particulier pour les objets

v0.6.67.3 - 15 février 2017
- corrections diverses proposées par Freddy_Gwendo
- refonte complète de la gestion des textes ajoutés par BG2EE (au-delà de 74106) : il s'agit désormais d'une traduction vérifiée couvrant environ 900 textes
- dans cette partie BG2EE, les récupérations de textes simples tels que "merci", "au revoir", "qu'est ce que vous voulez ?" ont été neutralisées (apport quasi nul, risque de mauvais adaptation au contexte, etc.)

v0.7.16.6 - 29 septembre 2018
- ajout majeur de contenu traduit
  * Quête de Rasaad dans SoA : dialogues, lieux, personnages (des noms de créatures peuvent ne pas être traduits)
  * Sous-titre des voix pour le personnage principal et pour Rasaad
  * Objets ajoutés par BG2EE
  * Sorts ajoutés par BG2EE
- fichier L_fr_FR.lua désormais copié dans override pour la compatibilité avec des mods GUI touchant aux textes
- corrections/améliorations diverses dans les textes repris de ToB (début de fusion de travaux 0 -> 500 environ)
- compléments de traduction pour BG2EE V2.5.16.6 (L_fr_FR.lua et de nouveaux textes dans BG2EE)
- procédure de désinstallation revue : il est possible de résinstaller le mod sans avoir du ménage à faire à la main
