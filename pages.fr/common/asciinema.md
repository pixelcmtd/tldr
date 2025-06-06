# asciinema

> Enregistre et rejoue les sessions de terminal, et également partageable sur asciinema.org.
> Plus d'informations : <https://docs.asciinema.org/manual/cli/usage>.

- Associe l’installation locale de `asciinema` avec un compte asciinema.org :

`asciinema auth`

- Crée un nouvel enregistrement (une fois fini, l'utilisateur sera questionné pour l'enregistrer localement ou l'envoyer en ligne) :

`asciinema rec`

- Crée un nouvel enregistrement et l'enregistre dans un fichier local :

`asciinema rec {{chemin/vers/enregistrement.cast}}`

- Rejoue un enregistrement depuis un fichier local :

`asciinema play {{chemin/vers/enregistrement.cast}}`

- Rejoue un enregistrement depuis asciinema.org :

`asciinema play https://asciinema.org/a/{{id_d_enregistrement}}`

- Crée un nouvel enregistrement, en limitant le temps d’inactivité au maximum à 2.5 secondes :

`asciinema rec {{[-i|--idle-time-limit]}} 2.5`

- Affiche la sortie complète d'un enregistrement local :

`asciinema cat {{chemin/vers/enregistrement.cast}}`

- Envoie un enregistrement local vers asciinema.org :

`asciinema upload {{chemin/vers/enregistrement.cast}}`
