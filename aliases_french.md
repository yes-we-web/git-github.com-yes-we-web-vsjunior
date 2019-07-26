![logo ALias](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Alias_logo.svg/220px-Alias_logo.svg.png)

Bonjour à tous, j'espère que vous allez bien ! C'est mon premier "article" donc j'espère que vous allez trouver ça plutôt cool :satisfied: .

Petite présentation tout d'abord , moi c'est [**Antoine Goncalves**](https://github.com/Antoine-Goncalves) !

Je suis en train de faire une formation pour pouvoir être Developpeur Web à Lesquin ( la formation s'appelle [**Yes We Web**](https://twitter.com/YesWeWebVT) ) ( du moins on essaie :grimacing: ) .

Donc j'ai décider de vous faire une petite présentation des alias :

-----

# :one: Qu'est ce qu'un alias :

----

Du coup qu'est-ce qu'un alias ?

Un alias est tout simplement un raccourci pour les commandes sur le terminal.

Du coup , avec les alias, imaginons on doit écrire un truc hyper long et qu'on répete tout le temps ( sachant je cite :

----

> Vous devez apprendre à être une féniasse by _**Hachemi**_

----

Du coup l'alias est le meilleur outils pour pouvoir gagner du temps et de l'énergie :v:

----

## :two: Comment créer un alias :

----

Deux moyens s'offrent à vous maintenant pour créer un alias :

* Dans le fichier `bashrc` juste après la ligne "some more ls aliases"

:bowtie: *le fichier `.bashrc` est déja créer donc pas de panique !* :bowtie:

* Ou bien ( et je conseille vivement l'option 2 ) de créer son propre fichier d'alias. Ça permet de ne pas surcharger le fichier `bashrc` et vous aurez un fichier exclusivement d'alias !

Du coup une fois qu'on as fait cette étape , pour créer son alias il faut juste taper :
```
alias nom_alias='commande de l'alias'
```

:bowtie: On peut parfaitement utiliser " ou ' c'est la même chose ça ne changera pas votre alias , les deux écritures sont bonnes :bowtie:

:bangbang: Attention :bangbang: **Il n'y a aucun espace entre le nom de l'alias, le signe = et la commande**

Une fois que vous avez créer un ou plusieurs alias , enregister vos modification et , hop , on retourne sur le terminal.

----

### :three: Comment les utilisés :

----

Encore une fois deux moyens s'offrent à vous :

* Soit on quitte tout simplement son terminal et on le redémarre pour pouvoir ajouter la modification

* Ou bien on tape :
```
source ~/.bashrc
```

:bangbang: Attention ! :bangbang: **Si vous voulez créer un nouveau fichier pour vos alias n'oubliez pas de le rajouter dans le fichier `.bashrc` , c'est à dire :**

**1. Allez dans le fichier `.bashrc`**

**2. Écrire juste en dessous des alias prédefini `source ~/nom_fichier_alias`**

On peut donc créer de nombreux alias pour pouvoir nous facilité la vie.

Votre alias est donc créer et prêt à étre utiliser , on tape donc :
```
nom_alias
```

Et ça vous fait gagner du temps !

Par exemple , pour y voir plus clair :

j'ai créer cette alias :
```
alias upd='sudo apt update'
```

dans le terminal , au lieu de taper `sudo apt update` j'ai juste `upd`.

:bowtie: Cette commande permet de mettre à jour la liste des packages existants. :bowtie:

Si on veut voir tout les alias qu'on as créer , suffit juste de taper :
```
alias
```

On peut également créer des alias temporaires ! Du coup pouur faire ça il faut juste taper sur son terminal :
```
alias nom_alias='commande alias'
```

Par exemple :
```
alias maj='sudo apt update && sudo apt upgrade'
```

:bowtie: && veut dire simplement *et* :bowtie:

Jusqu'à la fermeture du terminal, on peut taper :
```
maj
```

Enfin, on peut aussi supprimer l'alias de la session en cours du terminal, on tape :
```
unalias nom_alias
```

Pour reprendre l'exemple juste au dessus :
```
unalias maj
```

Voilà , Voilà !

J'espère que cette petite introduction aux alias aura permis à certain d'en savoir un peu plus, et pour les féniants ils seront encore plus content :joy:

~~Merci à vous !~~

**Antoine Goncalves**

:wave: :wave: :wave:
