# layout-challenge

## Brief :

### /index

+ une barre de menu en bas de l'écran
+ un seul bouton  

*ultra minimaliste* :bowtie:
![index](images/home.png)


+ tout est placé sur une grille de 4 colonnes (responsive la grille... on est pas des sauvages :grin:)

![grid](images/home-grid.png)

+ le menu s'ouvre en éventail
+ on a un maximum de 5/6 choix de formes, plus un bouton [MORE](#shape) qui ouvre une nouvelle page avec la liste de toutes les formes disponibles.

*on fait déjà moins les malins la !*
![menu](images/home-menu.png)

### /shape

+ liste de toutes les formes (toujours sur la grille)  
  Ici il n'y en a que 8 mais vous pouvez en mettre autant que vous voulez.  
  Notez aussi que je n'ai fait qu'un seul apperçu pour [CIRCLE](#shapeforme) mais il va évidemment falloir être moins fainéant que ça :grimacing:

*en fait il ne faudrait même pas afficher le bouton `SHAPES` quand on est sur `/shape` :see_no_evil:*
![list](images/shape.png)

### /shape/[forme]

+ quand on clique sur une forme (depuis la liste ou depuis le menu éventail) on passe sur sa page dédiée `/shape/[forme]`
+ on affiche une seule carte et le motif en background

*notez l'alignement entre l'aperçu de la carte et la position du background :art:*
![motif](images/shape-id.png)

### Note

Pour les images, vous pouvez éventuellement bidouiller mon sketch p5.js pas du tout terminé :  
https://editor.p5js.org/vincent-DelJesus/sketches/zmX5I8dDA  

C'est comme ça que j'ai fait l'image des cercles :

![tile](images/tile.png)

GO ! :checkered_flag: