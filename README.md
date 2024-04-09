<<<<<<< HEAD
**Nom :** Thomazeau-Agullo Louis

**Groupe :** 02-A

**Année :** 2024

**IUT Le Havre - Cours GIT**

### Compte-rendu TP3

Dans ce TP3 on apprend a inviter un collaborateur sur notre github (vue Athos) sinon on rejoint en tant que collaborateur (vue Porthos).

__git checkout <nom>__ pour se diriger vers une branch existante et l'option -b pour en créer une.

__git merge :__ permet de fusionner deux brancher, pour cela on se place sur le main puis on merge avec la branche créer en amont (test par exemple)
“Nous avons maintenant créé une nouvelle branche de test”

Question : Que se passe-t-il? Où est passé le fichier test.txt ?

Réponse : Nous ne voyons pas le fichier test.txt dans la branch main car nous avons créer une
deuxieme branch test, c'est donc dans cette dernière que nous l'avons créer.

Ayant switch de branch, bien évidemment, nous ne voyons plus apparaitre le fichier test.txt dans la branch main.

Question : Que se passe-t-il si nous tapons la commande ls ?

Réponse : Nous ponvons apercevoir que le fichier test.txt est apparue tout simplement parceque nous avons fusionner les deux branch existantes et donc nous pouvons maintenant voir dans le main (merging) le fichier test.txt
=======
# tp3

Question : Que se passe-t-il? Où est passé le fichier test.txt ?
Réponce  : Nous ne voyons pas le fichier teste.txt dans la branche main car nous avons créer une deuxième branche teste c'est donc cette dernière branche que nous avons créer qu'elle se trouve.

Question : Que se passe-t-il si nous tapons la commande ls ? :
Réponce  : Nous pouvons apercevoir que le fichier texte.txt car la cause de la fusion des deux branches.
>>>>>>> 866b988a66e132f903c3f45bb28a35a1980cf73e