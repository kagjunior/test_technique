# test_technique
Installation : 
  D'abord, j'ai utilisé un serveur (MAMP pour ma part). Après j'ai créé un dossier contenant tous les fichiers que j'ai mis en   ligne. Le dossier qui contient les fichiers flexsliders a été téléchargé ici : http://flexslider.woothemes.com/ .
Fonctionnement technique : 
  Dans la section <<header>>, j'ai utilisé 2 div. Le 1er div contient le logo et le 2ièm contient 2 autres div : le nav et le   texte. Ce dernier est placé presque au centre du header en utilisant le positionnement en css. Le mot shopify est souligné     par une image que j'ai extraite dans photopea et que j'ai mise en background dans le header. Le background-position m'a       permis d'avoir la position voulue.
  Dans la section <<portfolio>>, il y'a un div qui contient l'image des clients. le logo YOKO dirige vers son site. Comment ?
  D'abord j'ai créé un lien <a> qui dirige vers le site de yoko. Ensuite je lui ai donné une longueur et une largeur jusqu'à     pouvoir contenir le logo. En jouant avec le positionnement en absolute, j'ai superposé le lien sur le logo. Enfin, j'ai mis   le background du lien en transparent pour voir le fond.
  Dans la section <<slider>>, j'ai téléchargé le module flexslider utilisant jquery. Ce lib me permet de faire des slides. Le   contenu textuel est placé en position absolute.
  Dans la section <<texte infinite>>, le texte text défile à l'infini sans cascade. C'est grace à la propriété data-text de la   balise qui contient le text.
Difficultés :
  Il y a 2 choses que j'ai du mal à faire et que j'ai des pistes pour le faire.
  1) le fait de voir le début du slide suivant à droite.
    j'ai mis les 2 slides en position absolute, les mettre en inline-block, diminuer leur largeur. mais ça ne marche pas.
  2) le fait de changer l'icon de navigation en fléche.
    J'ai réussi à faire défiler les images en cliquant sur l'icon. Mon probléme est que quand je mets les fontawesomes pour       les icones de mon choix, ça ne marche pas.
 Responsive design mobile :
  J'ai mis le responsive en utilisant les media queries. il y a la partie nav qui est supprimée et qui sera mise en icon menu. Je n'ai pas encore fini le responsive design.
    
 
