# Compte-rendu TP2

## Exercice 1 
1) Bash cherche les commandes successivement dans /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin jusqu'à les trouver

2) La variable d'environnement HOME est celle utilisée si *cd* est utilisé sans argument

3) LANG correspond à la langue utilisé et l'encodage (FR et UTF-8 ).
PWD contient le répértoire courant.

OLDPWD contient le répértoire précédent.

SHELL correspond à l'emplacement du shell et là ou se trouve les commandes.

_ contient le répértoire de la commande *printenv* 

5) La commande BASH "ouvre" un nouvel environnement. La variable locale MY_VAR n'existe plus car elle n'était créée que localement dans la première console, le deuxième BASH ne la connait pas.

En revenant dans la première console avec *exit*, on retrouve la valeur de MY_VAR.

6) La variable MY_VAR étant cette fois une variable d'environnement, tout les BASH la connaitront car elle n'es plus locale.

8) *echo 'Bonjour à vous deux ' $NOMS*

9) unset va effacer la variable du système, alors que donner une valeur vide ne supprime pas cette variable.
Elle existe toujours mais ne contient rien.

10) *echo '$HOME = '$HOME*
