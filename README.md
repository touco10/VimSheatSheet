# VimSheatSheet
Sheat Sheet pour Vim# Cheat Sheet Vim

## Modes
- **Normal mode**: Press `Esc` to enter Normal mode from any other mode.
- **Insert mode**: Press `i` to enter Insert mode from Normal mode.
- **Command-line mode**: Press `:` to enter Command-line mode from Normal mode.

## Mouvement
- `h`: Déplacer le curseur vers la gauche.
- `j`: Déplacer le curseur vers le bas.
- `k`: Déplacer le curseur vers le haut.
- `l`: Déplacer le curseur vers la droite.
- `w`: Aller au mot suivant.
- `b`: Aller au mot précédent.
- `gg`: Aller au début du fichier.
- `G`: Aller à la fin du fichier.
- `0` (zéro): Aller au début de la ligne.
- `$`: Aller à la fin de la ligne.
- `Ctrl + f`: Faire défiler d'une page vers l'avant.
- `Ctrl + b`: Faire défiler d'une page vers l'arrière.

## Édition
- `x`: Supprimer le caractère sous le curseur.
- `dd`: Supprimer la ligne entière.
- `yy`: Copier la ligne entière.
- `p`: Coller après le curseur.
- `P`: Coller avant le curseur.
- `u`: Annuler la dernière action.
- `Ctrl + r`: Rétablir la dernière action annulée.
- `.` (point): Répéter la dernière commande.

## Recherche et remplacement
- `/motif`: Rechercher le motif vers l'avant.
- `?motif`: Rechercher le motif vers l'arrière.
- `n`: Aller à l'occurrence suivante.
- `N`: Aller à l'occurrence précédente.
- `:s/motif/remplacement/g`: Remplacer le motif par le remplacement dans la ligne courante.
- `:%s/motif/remplacement/g`: Remplacer le motif par le remplacement dans tout le fichier.

## Enregistrement et exécution de macros
- `q<lettre>`: Commencer à enregistrer une macro dans la lettre spécifiée.
- `q`: Arrêter l'enregistrement de la macro.
- `@<lettre>`: Exécuter la macro enregistrée dans la lettre spécifiée.
- `@@`: Exécuter la dernière macro utilisée.

## Enregistrement et exécution de commandes
- `:q`: Quitter Vim.
- `:w`: Enregistrer le fichier.
- `:wq`: Enregistrer le fichier et quitter Vim.
- `:q!`: Quitter Vim sans enregistrer les modifications.

## Autres commandes utiles
- `:help`: Afficher l'aide.
- `:e <nom_fichier>`: Ouvrir un fichier spécifique.
- `:bn`: Passer au fichier suivant dans la liste des tampons.
- `:bp`: Passer au fichier précédent dans la liste des tampons.
- `:sp <nom_fichier>`: Ouvrir un fichier dans une fenêtre horizontale.
- `:vsp <nom_fichier>`: Ouvrir un fichier dans une fenêtre verticale.
