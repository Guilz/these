# Ma thèse de doctorat

Ce dépôt contient tous les fichiers sources de la rédaction de ma thèse. 

Les commandes suivantes permettent de construire un fichier html ou docx, ou les
deux à la fois, quasi-complet (l'outil [pandoc](http://pandoc.org) doit être
installé) :

```
make html
make docx
make all
```

La mise en page obtenue est simple : les titres, tableau et figures ne sont pas
numérotés, certaines figures ne sont pas correctement à l'échelle, les tables
des matières, des tableaux et des figures ne sont pas construites, les sauts de
page nécessaires entre les sections ne sont pas ajoutés, et les annexes ne sont
pas incorporées au fichier généré.

Le [fichier PDF correspondant à la version finale][these-tel] est disponible
dans l'archive publique [Thèses en ligne][tel].
Une [copie auto-archivée][these-self-ar] est aussi accessible depuis
[mon site personnel][site-perso].


[these-tel]: https://tel.archives-ouvertes.fr/tel-01281310

[tel]: https://tel.archives-ouvertes.fr

[these-self-ar]: https://keybase.pub/guillawme/these/ 

[site-perso]: https://www.gaullier.org/fr/these/
