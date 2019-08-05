# Kata Doragon Bakuchi

Doragon Bakuchi (Le jeu du Dragon) est un Kata qui a pour but d'aborder plusieurs notions de la POO:

- Shameless code
- DRY
- SOLID
- Polymorphisme
- Refactoring
- ...

Ce Kata imagine un jeu de dés Japonais ou il faut lancer trois dés (inspiré du Kitsune bakuchi).

Notre objectif ici va être d'implémenter un petit programme qui retourne le score du joueur en fonction du résultat de ses dés.

Ce jeu étant en cours d'invention, il devra très certainement évoluer dans le temps...

## Règles du jeu:

- Si les trois dés sont similaire, on fait un "Doragon-en" (Flammes du dragon), qui est le plus fort combo possible.
- Si on a deux dés similaires on fait un "Sakana" (Poisson)
- Si les dés sont différents on fait un "Tokage" (Lézard)

- 🐊 | Lorsqu'on fait un "Tokage", on informe le joueur qu'il vient de perdre 5 points.

- 🐠 | Lorsqu'on fait un "Sakana", on informe le joueur qu'il vient de gagner 1 point.

- 🐉 | Pour connaitre le score d'un Doragon-en il faut additionner les trois dés et si la valeur est pair on ajoute 1.

## Débuter le kata:

- *Forkez* ce repo sur github

- *Clonez* le et créez un nouvelle branche *hajime* que vous *pushez*.

- *Envoyez le lien de cette branche à votre sensei !*

- Installez les dépendances `bundle install`.

Ce kata contient des tests qui sont `skip` par default, càd qu'ils ne s'exécutent pas.

- Enlevez le premier `skip` et lancez la suite de test. Vous devez maintenant avoir un test qui `fail`. Dès lors vous avez 4mn pour le faire passer au vert (sans modifier le test).

- À la fin des quatre minutes vous devez faire un commit et un push avec comme nom de commit "Test 1 from red to green !"

- Recommencez l'opération jusqu'à ce qu'il n'y ai plus de `skip` et que tous les tests soient vert.

- Pour finir vous pouvez refacto votre code avant de prévenir votre sensei !


