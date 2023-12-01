# --- Jour 1 : Trébuchet ?! ---

Il y a quelque chose qui cloche avec la production globale de neige, et vous avez été choisi pour y jeter un coup d'oeil. Les elfes vous ont même donné une carte. Sur celle-ci, ils ont utilisé des étoiles pour marquer les cinquante endroits les plus susceptibles d'avoir des problèmes.

Vous avez fait ça assez souvent pour savoir que pour réparer la production de neige, vous allez devoir vérifier les **cinquante étoiles** avant le 25 décembre.

Collectez les étoiles en résolvant les puzzles. Deux puzzles sont disponibles chaque jour du calendrier de l'avent, le deuxième puzzle étant débloqué quand vous terminez le premier. Chaque puzzle vous donne **une étoile***. Bonne chance !

Vous essayez de demander pourquoi ils n'utilisent pas tout simplement une [machine à météo](https://adventofcode.com/2015/day/1) ("pas assez puissante") et où ils vous envoient ("dans le ciel"), et puis pourquoi votre carte semble être majoritairement vide ("dis donc tu poses vraiment beaucoup de questions toi hein ?") et - et attendez est-ce que vous avez dit le CIEL ? ("Bien sûr, d'où penses-tu que viens la neige ?")

Vous réalisez alors que les elfes vous ont déjà chargé dans un [trébuchet](https://fr.wikipedia.org/wiki/Tr%C3%A9buchet) ("bouge pas s'il te plaît, il faut qu'on t'attache correctement").

Alors qu'ils terminent les ajustements finaux, vous découvrez que leur document de calibrage (l'entrée de votre puzzle) à été *amendé* par une très jeune elfe qui était visiblement très contente à l'idée de montrer ses talents artistiques. En conséquence, les elfes ont du mal à lire les valeurs du document.

Le document nouvellement amélioré consiste en plusieurs lignes de texte, chaque ligne servait à l'origine à contenir des *valeurs de calibrage* spécifiques que les elfes doivent désormais retrouver. Sur chaque ligne, la valeur de calibrage peut être trouvée en combinant le *premier chiffre* et le *dernier chiffre* (dans cet ordre) pour former un seul *nombre à deux chiffres*.

Par exemple :

```calibration-aoc
1abc2
pqr3stu8vwx
a1b2c3d4e5f
treb7uchet
```

Dans cet exemple, les valeurs de calibrage de chacune des quatre lignes sont `12`, `38`, `15` et `77`. Faire la somme ces valeurs donne *`142`*.

Prenez en compte la totalité du document de calibrage. *Quelle est la somme de toutes ses valeurs de calibrage "?*
