# un-hover-optimal-sur-un-bouton-par-deux-arrieres-plans
Le changement du background se fait de manière fluide grâce à une animation

Ici, la couleur du background ne change pas au survol, mais c'est le background
qui change. L'objectif est d'éviter d'animer la propriété background-color qui
nécessite des calculs, ce qui pourraît diminuer le FPS(frame per second) qui
doit être de 60fps pour que l'animation soit fluide.
