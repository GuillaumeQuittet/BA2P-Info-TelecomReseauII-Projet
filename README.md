# Projet de télécommunication et réseaux de BA2P

Ceci est le dépot servant à stocker les fichiers.

## Comment participer ?

- Téléchargez et installez Git (disponible [ici](https://git-scm.com/))

- Cliquez sur le bouton vert ***Clone or download***

![bouton-clone-or-download]

[bouton-clone-or-download]: https://github.com/GuillaumeQuittet/BA2P-Info-TelecomReseauII-Projet/blob/master/screenshots/bouton-clone-or-download.png

- Copiez collez l'url

- Ouvrez Git et avec la commande ***cd***, rendez-vous dans le dossier de votre choix.

- Tapez la commande suivante:

```
git clone https://github.com/GuillaumeQuittet/BA2P-Info-TelecomReseauII-Projet.git
```

- Rendez-vous dans le dossier ***BA2P-Info-TelecomReseauII-Projet***

- Tapez les commandes suivantes

```
git config --global user.email "you@exemple.com"
git config --global user.name "Guillaume Quittet"
```

Où :

- you@exemple.com = Votre email qui a servi à l'inscription pour créer votre compte Github.
- Guillaume Quittet = A remplacer par votre prénom et votre nom.

Ensuite pour sauvegarder tout le temps votre mot de passe, tapez cette commande :

```
git config --global credential.helper store
```

Voilà vous êtes fin prêt pour travailler sur le projet.

## Les règles à suivre

- On n'édite que sa partie et on ne touche pas aux fichiers des autres
- On met à jour ses fichiers locaux avant de travailler
- On ne push pas toutes les 2 secondes
- On ne met pas de bêtises dans les commits
- Dès qu'on a fini une partie, on push.

## Les commandes de Git

### Mettre à jour les fichiers locaux

```
git pull
```

### Voir les modifications par rapport au dépot

```
git status
```

### Ajouter ou supprimer des fichiers présent dans le résultat de la commande ***git status***

#### Tous les fichiers

```
git add *
```

#### Le fichier toto.txt

- Ajouter
```
git add toto.txt
```

- Supprimer
```
git rm toto.txt
```

#### Les fichiers tata.txt et toto.txt

- Ajouter
```
git add tata.txt toto.txt
```

- Supprimer
```
git rm tata.txt toto.txt
```

### Faire un commit

Chaque modification effectuée a besoin d'un commit (message). Cela permet de savoir ce qui a été fait et permet aussi de revenir à une version antérieure d'un fichier grâce à un ancien commit.

```
git commit -m "Mon message"
```

### Faire un push

Faire un push permet de mettre les fichiers modifiés sur le dépot
```
git push
```