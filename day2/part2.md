# --- Partie Deux ---

L'elfe dit qu'il a arrêté de produire de la neige puisqu'il n'a plus *d'eau* ! Il ne sait pas vraiment pourquoi l'eau s'est arrêtée, mais il peut vous montrer comment aller vers la source d'eau pour que vous puissiez vérifier. C'est tout droit !

Pendant que vous continuez à marcher, l'elfe vous pose une deuxième question : dans chaque partie que vous avez jouée, quel est le *plus bas nombre de cubes de chaque couleur* qui auraient pu être dans le sac pour que la partie soit possible ?

À nouveau, considérez l'exemple de parties de tout à l'heure :

```aoc-cubes
Game 1: 3 blue, 4 red; 1 red, 2 green, 6 blue; 2 green
Game 2: 1 blue, 2 green; 3 green, 4 blue, 1 red; 1 green, 1 blue
Game 3: 8 green, 6 blue, 20 red; 5 blue, 4 red, 13 green; 5 green, 1 red
Game 4: 1 green, 3 red, 6 blue; 3 green, 6 red; 3 green, 15 blue, 14 red
Game 5: 6 red, 1 blue, 3 green; 2 blue, 1 red, 2 green
```

- Dans la partie 1, la partie aurait pu être jouée avec au minimum 4 cubes rouges, 2 cubes verts et 6 cubes bleus. Si une des couleurs avait eu rien qu'un cube en moins, la partie aurait été impossible.
- La partie 2 aurait pu être jouée avec au minimum 1 cube rouge, 3 cubes verts et 4 cubes bleus.
- La partie 3 aurait pu être jouée avec au moins 20 cubes rouges, 13 cubes verts et 6 cubes bleus.
- La partie 4 nécessitait au moins 14 cubes rouges, 3 cubes verts et 15 cubes bleus
- La partie 5 n'avait besoin que de 6 cubes rouges, 3 cubes verts et 2 cubes bleus dans le sac

La *puissance* d'un ensemble de cubes est égale au nombre de cubes rouges, verts et bleus multipliés ensemble. La puissance de l'ensemble minimum de cubes de la partie 1 est `48`. Dans les parties 2 à 5, il s'agit de `12`, `1560`, `630` et `36` respectivement. Faire la somme de ces cinq puissances donne *`2286`*.

Pour chaque partie, trouvez l'ensemble minimum de cubes qui aurait dûs être présents. *Quelle est la somme des puissances de ces ensembles ?*
