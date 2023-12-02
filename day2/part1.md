# --- Jour 2 : Casse-tête de cubes ---

Vous êtes lancé très haut dans l'atmosphère ! Le sommet de votre trajectoire vous fait tout juste atteindre la surface d'une énorme île flottant dans le ciel. Vous atterrissez tout doucement dans un moelleux tas de feuilles. Il fait franchement froid, mais vous ne voyez pas beaucoup de neige. Un elfe arrive pour vous accueillir.

L'elfe explique que vous êtes arrivé à *l'Île Neige* et demande pardon pour le manque de... neige. Il se ferait un plaisir de vous expliquer la situation, mais il y a un peu de marche à faire pour parvenir à l'endroit posant problème, vous avez donc tout votre temps. Ils n'ont pas souvent de visiteurs là-haut, ça vous dirait de jouer à un jeu en attendant ?

Pendant que vous marchez, l'elfe vous montre un petit sac et des cubes qui sont soit rouges (`red`), soit verts (`green`), soit bleus (`blue`). Chaque fois que vous jouez à une partie (`game`) de ce jeu, il cache un nombre secret de cubes de chaque couleur dans le sac, et votre but est de récupérer des informations sur le nombre de cubes.

Pour obtenir des informations, une fois que le sac a été chargé en cubes, l'elfe ira chercher dans son sac un nombre aléatoires de cubes, vous les montrera, puis les remettra dans le sac. Il le fera quelques fois par partie.

Vous jouez donc à quelques parties et enregistrez les informations de chacune d'elles (l'entrée de votre puzzle). Chaque partie est listée avec son numéro d'identification (par exemple, `11` dans "``Game 11:...``) suivie par une liste de sous-ensembles révélés depuis le sac, séparés par des point-virgules (par exemple `3 red, 5 green, 4 blue` pour un sous-ensemble).

L'enregistrement de quelques parties pourrait donc ressembler à ça :

```aoc-cubes
Game 1: 3 blue, 4 red; 1 red, 2 green, 6 blue; 2 green
Game 2: 1 blue, 2 green; 3 green, 4 blue, 1 red; 1 green, 1 blue
Game 3: 8 green, 6 blue, 20 red; 5 blue, 4 red, 13 green; 5 green, 1 red
Game 4: 1 green, 3 red, 6 blue; 3 green, 6 red; 3 green, 15 blue, 14 red
Game 5: 6 red, 1 blue, 3 green; 2 blue, 1 red, 2 green
```

Dans la partie 1, trois ensembles de cubes sont révélés depuis le sac (et ensuite remis dedans). Le premier ensemble contient 3 cubes bleus et 4 cubes rouges ; le deuxième ensemble contient 1 cube rouge, 2 cubes verts et 6 cubes bleus ; et le troisième ensemble ne contient que 2 cubes verts.

L'elfe voudrait tout d'abord savoir combien de parties auraient été possibles si le sac ne contenait *que 12 cubes rouges, 13 cubes verts et 14 cubes bleus* ?

Dans l'exemple ci-dessus, les parties 1, 2 et 5 auraient été *possible* si le sac était chargé avec cette configuration. Cependant, la partie 3 aurait été *impossible* puisqu'à un moment, l'elfe a sorti 20 cubes rouges du sac en une seule fois. De la même manière, la partie 4 aurait également été *impossible* puisque l'elfe vous a montré 15 cubes bleus en une seule fois. Si vous additionnez les identifiants des parties qui aurait été possibles, vous obtenez *`8`*

Déterminez quelles parties aurait été possibles si le sac avait été chargé de seulement 12 cubes rouges, 13 cubes verts et 14 cubes bleus. *Quelle est la somme des identifiants de ces parties ?*
