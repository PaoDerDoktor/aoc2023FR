# --- Jour 4 : Tickets à gratter ---

La télécabine vous fait monter. Mais étrangement, le sol ne semble pas monter avec vous : vous n'escaladez pas une montagne. Alors que le cercle de l'Île Neige disparaît de votre champs de vision, une toute nouvelle masse de terre apparaît soudainement devant vous ! La cabine vous amène sur la surface d'une toute nouvelle île, et s'engouffre dans sa station.

Quand vous sortez de la cabine, la première chose que vous remarquez est que l'air est bien plus *chaud* que sur l'Île Neige. Il est aussi plutôt *humide*. Est-ce que vous êtes à l'endroit de la source d'eau ?

Ensuite, vous remarquez qu'un elfe est assis sur le sol à l'autre bout de la station, dans ce qui semble être une pile de tickets carrés en papier coloré.

"Oh ! Bonjour !", vous dit-il. L'elfe court vers vous, visiblement content d'avoir de la visite. "Comment puis-je vous aider ? - Oh, vous voulez en savoir plus sur la source d'eau ?"

"Je sais pas trop, je ne fais que faire fonctionner cette station de télécabines. Mais ça sonne comme quelque chose qu'on devrait avoir, par contre. Nous sommes sur l'Île Île, après tout ! Je suis sûr que le *jardinier* saurait vous aider. Mais il est sur une autre île - enfin euh, les petites îles, celles entourées d'eau, pas les flottantes. Il faut vraiment qu'on trouve un meilleur système de nommage. Enfin bref, j'vais vous dire : si vous pouvez m'aider sur un problème vite zef, je vous laisse *emprunter mon bateau* et vous pouvez aller directement voir avec le jardinier. J'ai reçu une tonne de [tickets à gratter](https://fr.wikipedia.org/wiki/Jeu_de_grattage) en cadeau, mais je n'arrive pas à savoir ce que j'ai gagné."

L'elfe vous emmène vers la pile de tickets colorés. Là-bas, vous découvrez des dizaines de tickets à gratter, tous ayant leur cache opaque déjà retirés. En en prenant une, vous remarquez que chaque ticket possède deux listes de nombres, séparées par une barre verticale (`|`) : une liste de *numéros gagnants* puis une liste de *numéros choisis*. Vous organisez les informations dans une liste (l'entrée de votre puzzle).

De ce qu'à compris l'elfe, vous devez trouver quels *numéros choisis* apparaissent dans la liste de *numéros gagnants* correspondante. Chaque numéro gagnant choisi donne *un point*, et numéro gagnant choisi supplémentaire *double* la valeur en points du ticket.

Par exemple

```aoc-scratchcards
Card 1: 41 48 83 86 17 | 83 86  6 31 17  9 48 53
Card 2: 13 32 20 16 61 | 61 30 68 82 17 32 24 19
Card 3:  1 21 53 59 44 | 69 82 63 72 16 21 14  1
Card 4: 41 92 73 84 69 | 59 84 76 51 58  5 54 83
Card 5: 87 83 26 28 32 | 88 30 70 12 93 22 82 36
Card 6: 31 18 13 56 72 | 74 77 10 23 35 67 36 11
```

Dans l'exemple ci-dessus, le ticket 1 possède cinq numéros gagnants (`41`, `48`, `83`, `86` et `17`) et huit numéros choisis (`83`, `86`, `6`, `31`, `17`, `9`, `48`, `53`). De tous les numéros choisis, quatre (`48`, `83`, `17` et `86`) sont des numéros gagnants ! Ce qui signifie que le ticket 1 vaut *`8`* points (1 pour le premier numéro, puis doublé pour chacun des trois numéros après le premier).

- Le ticket 2 comporte deux numéros gagnants (`32` et `61`) et vaut donc *`2`* points.
- Le ticket 3 comporte deux numéros gagnants (`1` et `21`) et vaut donc *`2`* points.
- Le ticket 4 comporte un numéro gagnant (`84`) et vaut donc *`1`* points.
- Le ticket 5 ne comporte pas de numéro gagnant et ne vaut donc aucun point.
- Le ticket 6 ne comporte pas de numéro gagnant et ne vaut donc aucun point.

Dans cet exemple, la pile de tickets à gratter de l'elfe vaut *`13`* points.

Lancez-vous dans la grande pile de tickets colorés. *Combien de points vaut-elle au total ?*
