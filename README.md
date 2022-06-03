 # P3 - OhMyFood
## Infos  
Projet réalisé dans le cadre de la formation Développement Web par OpenClassroom [P3].  
Page conçu en mobile first.  

## Versions 

### V1.1.2 

* Changement de nom sur certaines animations "Aggrandir" pour éviter conflits.  

### v1.1.1

* animation flêche retour arriere menu.  
* Mise en forme titre h2 page menu.  
    - Modification police + rajout bordure paramétrable + majuscules.  
* Gestion des titres de plats trop longs.  
    - création mixin ellipsis
* Vérification animations et réglages sur liste des plats.  
    - Modification et réglages durée/sens. +fluide  
* Validation W3C  
    - index ok  
    - Menu modification title/alt pour a/img  
* Ajout hidden sur loading spinner  
* Modififaction animation Favoris  
* Modification version desktop & gestion image assiete exemple.  
* Refactoring/relecture SASS/CSS  
* Run Autoprefixer  

*** 

### v1.1.0

* Version Tablette & Desktop  
    - Bouton valider  
    - Cases Fonctionnement  
    - class recentrage-desktop, pour ne pas toucher au body et garder le bg sur toute la largeur.    
* Modification taille bouton valider plat, avec variable.  
* Rédaction Pages Menu supplémentaires  
    /!\ Le restaurant "La note enchantée" a 4 entrées, ce qui implique un petit décallage sur l'animation du plat.   
    Difficile de gérer sans récupération dynamique du nombre de plat. J'incrémente à 4, à voir.  

***

### v1.0.6

* Rajout proriété pointer sur favoris  
* Animations Loading spinner  
/!\ Enlever commentaire dans HTML pour visualiser.  (L13 & L26)
* Animation #menu  - Paramètrable selon Nb Plat & Nb catégories de plat  
* Renommage des classes -- en _  
    - ok Menu  
    - ok index  

***

### v1.0.5

* Modification couleur bg dans page menu ddr -> dr  
* Début animations : + mixins ::after & :hover  
* Fonctionnement  
* Bouton valider  
* Div Card-plat--valider (avec width, à confirmer)  
* Bouton favoris + ajustement position/dimensions  
    - le CSS class favoris est passée en section _buttons pour gestion sur accueil + menu  
* hover sur lien footer  
* Mise en forme README  

***

### v1.0.4

* Mise en forme page unique "A la francaise"  
* Mise en forme conforme maquette - hors animations & media querries   
* Ajout fichier menu-restaurant.scss / Supression form & nav  
* Mise en forme du README.  

***

### v1.0.3

* Mise en forme section Fonctionnement  
* Mise en forme section Liste restaurants  
    - Ajout favoris + nouveau  
* Ajout icones dans footer  
* Ajout des mixins flex row/column  
* Hors animation & hors responsive, page d'accueil complète.  

***

### v1.0.2

* Ajout des fonts & couleurs  
* MAJ Page-menu exemple avec texte maquette.  
* Déclaration des styles globaux  
* Mise en forme header + footer.  
* Mise en forme sur la structure pour de la lisibilité.  
* *Finition à faire sur les couleurs bg/font  

***

### v1.0.1

* Rédaction accueil + page-menu exemple + structure header/section/footer  
* Ajout Div avec class & id  
* Implementation SASS avec structure 7.1  

***