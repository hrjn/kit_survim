# Kit de survi(m)

![xkcd_comic](img/xkcd_378.png)

*Credits:* [http://www.xkcd.com/378/](http://www.xkcd.com/378/)


Ci-dessous quelques commandes utiles pour s'y retrouver dans vi(m). Cette liste est lise à jour à fur et à mesure des découvertes de ces fameuses commandes et sert de pense-bête personnel.

Notations:

* *n* désigne un entier
* *c* désigne un caractère
* *s* désigne une chaîne de caractères


### Ouverture/fermeture/enregistrement
| Action | Commande |
| --- | :---: |
| Ouvrir le fichier *file* | `:o <file> `|
| Enregistrer les modifications dans le fichier *file* | `:w <file>` |
| Fermer et quitter le fichier courant | `:q` |
| Fermer et quitter sans enregistrer | `:q!` |


### Déplacement

| Action | Commande |
| --- | :---: |
| Aller en fin de ligne | `$` |
| Aller en fin de ligne + INS | `A` |
| Revenir en début de ligne | `0` |
| Aller à la ligne *n* | `<n>G` |
| Avancer le curseur de *n* mots | `<n>w` |
| Aller à la fin du fichier | `G` 
| Aller au début du fichier | `gg` |


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

### Couper/Copier-coller/Insérer

| Action | Commande |
| --- | :---: |
| Copier ligne courante | `yy` |
| Couper ligne courante | `dd` |
| Coller ligne coupée sous le curseur | `p` |
| Insérer le contenu di fichier *file* après le curseur | `:r <file>` |

### Rechercher

| Action | Commande |
| --- | :---: |
| Rechercher *s* | `/<s>` |
| Suivant | `n` |
| Précédent | `N` |
| Aller à la parenthèse fermante (ou ouvrante) associée | `%` |


### Remplacer

| Action | Commande |
| --- | :---: |
| Remplacer le caractère courant par *c* | `r<c>` |
| Remplacer reste du mot par *s* | `ce<s>` |
| Remplacer reste de la ligne par *s* | `c$<s>` |
| Remplacer *s1* par *s2* | `s/<s1>/<s2>/g` |
| Remplacer *s1* par *s2* (avec demande systématique de confirmation) | `s/<s1>/<s2>/gc` |
| Remplacer *s1* par *s2* entre les lignes *n1* et *n2* | `<n1>,<n2>s/<s1>/<s2>/g` |


### Position et état du fichier

| Action | Commande |
| --- | :---: |
| Afficher position et état | `Ctrl+G` |


### Exécution de commandes externes
| Action | Commande |
| --- | :---: |
| Lancer la commande *cmd* | `:!<cmd>` |

### Sélection de texte
| Action | Commande |
| --- | :---: |
| Passer en mode "visuel" et sélectionner le contenu derrière le curseur | `v` (+dépl. curseur) |
 
