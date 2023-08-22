# corrolaire
Projet de livre de recueil d'exercices corrigés rédigé avec LaTex

Le livre 'Corrolaire' est un recueil d'exercices corrigés de Mathématiques, Physique et Informatique de la première année de Mathématiques-Physique-Informatique.
Les exercices sont essentiellement tirés des devoirs de l'Université Nazi-Boni de Bobo Dioulasso au Burkina Faso. La plupart des exercices sont corrigés, il y a néanmoins quelques-uns qui ne le sont pas pour stimuler votre esprit de recherche.

Ce projet utilise `tcolorbox` pour gérer l'environnement `Exolist` et surtout, `tcbrecord` de `tcolorbox` fait la plus grande magie de ce template :
Les exercices et leurs corrigés sont saisis dans un seul fichier et l'environnement `Exolist` se charge d'afficher chaque contenu à la page qu'il faut. Les solutions des exercices sont à la fin du document et insérés à l'aide `savelowerto` de la macro `NewTColorBox`.
Le fichier main est assez commenté (et beaucoup confus, je l'avoue...) pour être compris.
