1 Introduction


1.1 Cadre du projet


Ce projet est réalisé dans le cadre du cours de Génie Logiciel et Programmation Orientée Objet
IN204 enseigné à ENSTA Paris par Bruno Monsuez. Le langage de programmation utilisé est
le C++. Parmi les sujets proposés nous avons choisi de réaliser un tetris multiplayer. Pour
cela nous avons utilisé deux bibliothèques : SFML (Simple and Fast Multimédia Library) pour
la gestion du réseau et SDL2 (Simple DirectMedia Layer) pour les graphismes.


1.2 Cahier des charges


Le programme doit permettre de jouer au jeu Tetris avec les mêmes règles que dans le jeu
original. On doit pouvoir afficher le nombre de lignes complétées, les points et le niveau. Avant
le début d’une nouvelle partie on doit pouvoir choisir son niveau qui se traduira par différentes
vitesses de chute pour les tetriminos.
Le multijoueur doit pouvoir être activé par simple pression d’une touche sur les ordinateurs des
deux joueurs. Chaque joueurs doit continuer de voir son jeu mais aussi celui de l’autre sur son
ordinateur.




2 Compilation


Notre logiciel a été développé pour être utilisé sur des ordinateurs sous Linux. Pour pouvoir
Utiliser correctement notre programme, il est nécessaire d’installer les librairies SFML et SDL2.
Une fois les librairies installées il suffit de se rendre dans le dossier tetris et de taper en ligne de
commande "make all". Cela produit deux exécutables, "tetris main" et "tetris multi main".
En fonction du mode de jeu souhaité l’utilisateur choisira de lancer l’un ou l’autre avec les
commandes : "./tetris_main" ou "./tetris_multi_main".




3 Description fonctionnelle


Une fois le jeu lancé avec les instructions précédentes il suffit de taper la touche espace pour
lancer une partie. Le contrôle des tetriminos se fait avec les touches flèches du clavier. Les touches
C et J permettent respectivement de créer une partie multijoueur et de rejoindre un autre
joueur.

