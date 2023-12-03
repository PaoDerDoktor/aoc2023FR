# --- Jour 03 : Rapports de Transmission  ---

L'elfe et vous arrivez finalement à une station de [télécabines](https://fr.wikipedia.org/wiki/T%C3%A9l%C3%A9cabine). Il vous dit que les télécabines vous emmèneront à la *source d'eau*, mais que lui ne vous accompagnera pas plus loin. Vous entrez.

Vous trouvez très vite les télécabines, mais il y a un petit souci : elles ne bougent pas.

"Aaah !"

Vous vous retournez et vous vous retrouvez nez-à-nez avec une elfe couverte d'huile de moteur avec une clé à molette et un air surpris. "Désolée, je n'attendais personne ! Les télécabines ne fonctionnent pas pour le moment, et j'en ai pour un bout de temps pour les réparer", dit-elle. Vous proposez votre aide.

L'ingénieure vous explique que l'une des pièces du moteur semble manquer, mais personne n'arrive à savoir laquelle. Si vous arrivez à *additionner tous les numéros de série des pièces* sur le schéma du moteur, vous devriez pouvoir facilement deviner quelle pièce manque.

Le schéma du moteur (l'entrée de votre puzzle) consiste en une représentation visuelle de celui-ci. On y voit beaucoup de nombres et de symboles que vous ne comprenez pas vraiment, mais apparemment, *n'importe quel nombre adjacent à un symbole*, même diagonalement, est un "numéro de série" et devrait être inclut dans votre somme.

Voici un exemple de schéma de moteur :

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

Dans ce schéma, deux nombres ne *sont pas* des numéros de série puisqu'ils ne sont pas adjacents à un symbole : `114` (en haut à droite) et `58` (au milieu à droite). Tous les autres nombres sont adjacents à un symbole, et *sont* donc des numéros de série. Leur somme vaut *`4361`*.

Bien sûr, le véritable schéma du moteur est bien plus grand. *Quelle est la somme de tous les numéros de série sur le schéma du moteur ?*
