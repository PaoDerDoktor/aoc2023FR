# --- Partie Deux ---

Au moment où vous alliez donner votre résultat à l'elfe, l'un d'entre vous comprends que les règles étaient en réalité imprimées au dos de chaque ticket pendant tout ce temps.

Il n'existe pas de système de "points". À la place, chaque ticket à gratter vous *fait d'autres tickets à gratter*, autant que vous avez choisi de numéros gagnants.

Pour être exact, vous gagnez des *copies* des tickets à gratter en-dessous du ticket que vous étudiez, autant que de numéros gagnants choisis. Ainsi, si le ticket 10 avait 5 numéros gagnants choisis, vous gagneriez une copie de chacun des 5 tickets en-dessous dans la liste : 11, 12, 13, 14 et 15.

Les copies des tickets sont évalués comme des tickets à gratter normaux et ont les *mêmes numéros et identifiant* que celui qu'ils copient. En conséquence, si vous gagniez une copie du ticket 10, ticket 10 qui vous donnait comme plus tôt 5 nombres gagnants choisis, la copie gagnerait elle aussi une copie de chacun des tickets que gagne l'original : 11, 12, 13, 14 et 15. Ce procédé se répète jusqu'à ce qu'aucune des copies ne vous fasse plus gagner de ticket (les tickets ne vous feront jamais gagner des tickets au-delà de la liste).

Cette fois, l'exemple d'au-dessus donne un résultat différent :

```aoc-scratchcards
Card 1: 41 48 83 86 17 | 83 86  6 31 17  9 48 53
Card 2: 13 32 20 16 61 | 61 30 68 82 17 32 24 19
Card 3:  1 21 53 59 44 | 69 82 63 72 16 21 14  1
Card 4: 41 92 73 84 69 | 59 84 76 51 58  5 54 83
Card 5: 87 83 26 28 32 | 88 30 70 12 93 22 82 36
Card 6: 31 18 13 56 72 | 74 77 10 23 35 67 36 11
```

- Le ticket 1 présente quatre numéros gagnants choisis, vous gagnez donc une copie de chacune des quatre tickets suivants : les tickets 2, 3, 4 et 5.
- Le ticket 2 original a deux numéros gagnants choisis, vous copiez donc les tickets 3 et 4.
- Votre copie du ticket 2 gagne elle aussi une copie de chacun des tickets 3 et 4.
- Vos quatre instances du ticket 3 (l'originale et ses trois copies) ont deux numéros gagnants choisis, vous gagnez donc *quatre* copies des tickets 4 et 5.
- Vos huit instances du ticket 4 (l'original et ses sept copies) ont un numéro gagnant choisi, vous gagnez donc *huit* copies du ticket 5.
- Vous quatorze instances du ticket 5 (l'original et ses treize copies) n'ont pas de numéros gagnants choisis, et vous ne gagnez donc aucun autre ticket.
- Votre instance du ticket 6 (l'originale, qui n'a pas été copiée) n'a pas de numéros gagnants choisis, et vous ne gagnez donc aucun autre ticket.

Une fois que tous les tickets originaux et toutes les copies aient été évalués, vous finissez avec *`1`* instance du ticket 1, *`2`* instances du ticket 2, *`4`* instances du ticket 3, *`8`* instances du ticket 4, *`14`* instances du ticket 5 et *`1`* instance du ticket 6. Au total, cette exemple de pile de tickets à gratter vous fait avoir *`30`* tickets !

Évaluez tous les tickets à gratter originaux et copiés jusqu'à ce qu'aucun autre ticket ne soit gagnable. En incluant les originaux, *avec combien de tickets à gratter finissez-vous ?*
