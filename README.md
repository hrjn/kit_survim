# Kit de survi(m)

![xkcd_comic](img/xkcd_378.png)

*Credits:* [http://www.xkcd.com/378/](http://www.xkcd.com/378/)


Ci-dessous quelques commandes utiles pour s'y retrouver dans vi(m). Cette liste est lise à jour à fur et à mesure des découvertes de ces fameuses commandes et sert de pense-bête personnel.

### Déplacement

| Action | Commande |
| --- | :---: |
| Aller en fin de ligne | `$` |
| Aller en fin de ligne + INS | `A` |
| Revenir en début de ligne | `0` |
| Aller à la ligne *n* | `<n>G` |
| Avancer le curseur de *n* mots | `<n>w` |

### Effacements

| Action | Commande |
| --- | :---: |
| Effacer caractère courant | `x` |
| Effacer mot courant | `dw` |
| Effacer *n* prochains mots (courant inclus) | `d<n>w` |
| Effacer reste de ligne | `d$` |
| Effacer ligne entière | `dd` |
| Effacer *n* prochaines lignes | `<n>dd` |

### Ctrl-Z
| Action | Commande |
| --- | :---: |
| Annuler | `u` |
| Récupérer ligne enitère | `U` |
