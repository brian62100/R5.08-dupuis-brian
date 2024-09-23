###### fait par brian dupuis
# Documentation du jeu de dame faite sur Python

# Somaire

1. Lancer le jeu
2. Comment se déplacer
3. La prise de pion
4. Transformation des pièces

## Sous-titre 1 : lancer le jeu

Il suffit d'ouvrir le fichier avec un logiciel de programmation et de lancer le programme. Il n'y a qu'un seul fichier le jeu se lancera alors dans le terminal

## Sous-titre 2 : comment se deplacer

Une fois le jeu lancé, il suffit au joueur de mettre les coordonnées du pion qui veut se déplacer, puis de mettre les coordonnées de la case. D'abord la cologne de faire entrer, puis de mettre la ligne. Dans le terminal, il sera précisé quel joueur doit jouer et quel cordonnier rentre en premier, les pions des joueurs seront :
* BN pour le pion blanc
* BR pour la reine blanche
* NN pour le pion noir
* NR pour la reine noire

### les pions
Les pions se déplacent sur les diagonales de 1 en 1 et seulement de cette façon, mais attention pour la prise faudra préciser la case d'après, si l'opération est valide alors il se fera sinon il redemandera au joueur ce qu'il veut faire

### les reines
Les reines peuvent se déplacer sur toutes les lignes droites de la reine, donc il faudra  mettre les coordonnées de la case voulue. Si c'est possible. Sinon, le déplacement se fera fait, sinon s'il n'est pas valide alors il redemera les coordonnées

## Sous-titre 3 : la prise de pion

Il faudra mettre les cordonniers du pion qu'on veut déplacer, puis mettre les cordonniers du pion qu'on veut prendre. On peut aussi faire des prises multiples. Une fois que le cordonnier de la case a été mis et que le pion a bougé, il sera possible de redeplacer ce pion si et seulement s'il peut directement reprend un pion.

## sous-titre 4 : transformation des pièces

Une fois qu'un pion a atteint l'autre côté du plateau, elle se transformera automatiquement en reine, la reine comparée au pion qui se déplace diagonalement se déplacera en ligne droite de chacun des 4 côtés. Elle pourra aller aussi loin qu'elle le voudra tant que le déplacement n'est pas bloqué et pourra donc prendre plusieurs pièces en même temps beaucoup plus facilement qu'un simple pion
