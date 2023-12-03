# --- Partie Deux ---

L'ingénieure trouve la pièce manquante et l'installe dans le moteur ! Alors que le moteur prends vie, vous sautez dans la télécabine la plus proche, enfin prêt à monter vers la source d'eau.

Par contre, vous n'avez pas l'air d'aller très vite. Peut-être qu'il y a encore un souci ? Heureusement, la cabine comporte un téléphone marqué "aide". Vous le prenez et l'ingénieure vous répond.

Avant que vous ne pouviez expliquer la situation, elle suggère que vous regardiez par la fenêtre. Vous y voyez l'ingénieure, tenant un téléphone d'une main et vous faisant "coucou" de l'autre. Vous allez si lentement que vous n'avez même pas quitté la station. Vous sortez de la cabine.

La pièce manquante n'était en fait pas le seul problème : un des engrenages installés dans le moteur n'est pas le bon. Un *engrenage* est un symbole `*` adjacent à *exactement deux nombres*. Son *rapport de transmission* est le résultat de la multiplication de ces deux nombres entre eux.

Cette fois, vous devez trouvez le rapport de transmission de chaque engrenage et tous les additionner, de sorte à ce que l'ingénieure trouve l'engrenage à remplacer.

Considérez à nouveau le schéma d'exemple :

```aoc-gear-schematic
467..114..
...*......
..35..633.
......#...
617*......
.....+.58.
..592.....
......755.
...$.*....
.664.598..
```

Sur ce schéma, on trouve *deux* engrenages. Le premier est en haut à gauche, il a les numéros de série `467` et `35`, son rapport de transmission est donc `16345`. Le second engrenage est en bas à droite, son rapport de transmission est de `451490` (le `*` adjacent à `617` *n'est pas* un engrenage puisqu'il n'est adjacent qu'à un seul numéro de série). Additionner tous ces rapports de transmission donne *`467835`*.

*Quelle est la somme de tous les rapports de transmission dans votre schéma de moteur ?*
