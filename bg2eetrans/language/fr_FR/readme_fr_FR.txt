Ce mod installe une traduction partielle des textes pour BG2EE à partir des textes de BG II + ToB (original) et de la traduction de BGEE (V2.3).

Remarque : le mod est basé sur une recherche de correspondance entre les textes en anglais de BG2EE et ceux de BG II + ToB et de BGEE date des versions 2.3 de BG2EE et de BGEE. Par conséquent il ne remplace en français que les textes suffisamment proches en anglais. Lorsque les textes de BG2EE ont trop changé par rapport à BG II + ToB, le mod préfère préserver le texte anglais plutôt que remplacer par une traduction qui pourrait s'avérer fausse, particulièrement pour les aspects techniques du jeu (description des classes, kits, sorts, objets).

Par ailleurs le mod modifie la liste de langues disponibles dans BG2EE (V2.0 et supérieur) afin d'ajouter le français dans la liste.


Historique
----------
Remarque : la version s'écrit sous la forme X.Y.révision_du_jeu
La révision du jeu est la révision de BG2EE à partir de laquelle l'algorithme de recherche de correspondance de textes avec ceux de ToB et BGEE a été faite. Ce n'est pas nécessairement la dernière en cours. Cette révision n'a pas d'incidence sur la compatibilité du mod avec une version particulière du jeu.
La conséquence est que les textes ajoutés par Beamdog après la révision indiquée ne sont pas pris en compte et resteront en anglais quoi qu'il arrive. En cas de modification de texte, le mod ne tiendra pas non plus compte du changement. Néanmoins le risque est assez faible qu'il y ait eu des changements remettant en cause la validité du choix de reprendre la traduction d'origine ou de laisser le texte en anglais.

V0.1.2050 : janvier 2014
- version non diffusée ayant permis de générer les fichiers dialog.tlk et dialogF.tlk mis à disposition pour les versions 1.2 et ultérieurement 1.3 de BG2EE

V0.2.2064
- prise en compte de BG2EE V2.x ; ajout de la langue française dans BGEE.lua afin qu'elle soit accessible dans l'écran des options
- ajout du fichier de traduction de l'interface du jeu pour BG2EE V2.x

V0.3.2064
- correction du fichier de traduction de l'interface
- différentiation Windows / Linux et Mac sur la manière de lancer l'installation des textes (retour de zelurker)
- complément de détection d'erreur pour signaler l'utilisation d'une version insuffisante de WeiDU pour BG2EE V2.x

v0.4.67.3
- récupération d'une centaine de traductions depuis BGEE V2.3.67.3
- ajout de notes sur la version française (idée de zelurker)
- nombreuses corrections de correspondances de textes grâce aux efforts de dricks, zelurker, Luren et Freddy_Gwendo
  * des correspondances inexactes ont été corrigées
  * des correspondances nouvelles ont été vérifiées, ce qui augmente le nombre de textes traduits
  * restauration de voix et de sons ayant disparu ou incorrects (notamment sur des personnages recrutables)

v0.5.67.3
- Modification de la récupération de texte à partir de BGEE pour qu'elle ne prenne pas le pas sur de meilleurs textes trouvés dans ToB
- Nombreuses améliorations et corrections diverses de Freddy_Gwendo
  * respect de l'affichage avec ou sans majuscule initiale pour les noms de kits
  * corrections de mots, uniformisation avec les EE (ensorceleur, cavalier), retraits des "Utilisable par" restants
  * uniformisation de l'affichage des bonus des armes +n (sans espace)
  * des correspondances nouvelles ont été vérifiées, ce qui augmente le nombre de textes traduits, en particulier pour les objets

v0.6.67.3
- Corrections diverses proposées par Freddy_Gwendo
- Refonte complète de la gestion des textes ajoutés par BG2EE (au-delà de 74106) : il s'agit désormais d'une traduction vérifiée couvrant environ 900 textes
- Dans cette partie BG2EE, les récupérations de textes simples tels que "merci", "au revoir", "qu'est ce que vous voulez ?" ont été neutralisées (apport quasi nul, risque de mauvais adaptation au contexte, etc.)
