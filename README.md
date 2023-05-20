# Cheat Sheet Vim

## Modes

- **Normal mode**: Mode par défaut pour naviguer et effectuer des opérations sur le texte.
- **Insert mode**: Mode pour insérer du texte.
- **Visual mode**: Mode pour sélectionner du texte.
- **Command-line mode**: Mode pour exécuter des commandes Vim.

## Mouvement du curseur

- `h`: Déplacer le curseur d'un caractère vers la gauche.
- `j`: Déplacer le curseur d'une ligne vers le bas.
- `k`: Déplacer le curseur d'une ligne vers le haut.
- `l`: Déplacer le curseur d'un caractère vers la droite.
- `w`: Aller au début du mot suivant.
- `b`: Aller au début du mot précédent.
- `e`: Aller à la fin du mot suivant.
- `0`: Aller au début de la ligne.
- `$`: Aller à la fin de la ligne.
- `gg`: Aller au début du fichier.
- `G`: Aller à la fin du fichier.

## Édition du texte

- `i`: Passer en mode Insert avant le curseur.
- `a`: Passer en mode Insert après le curseur.
- `o`: Insérer une nouvelle ligne en dessous de la ligne courante.
- `O`: Insérer une nouvelle ligne au-dessus de la ligne courante.
- `x`: Supprimer le caractère sous le curseur.
- `dd`: Supprimer la ligne courante.
- `yy`: Copier la ligne courante.
- `p`: Coller le contenu du presse-papiers.
- `u`: Annuler la dernière action.
- `Ctrl + r`: Rétablir l'action précédemment annulée.

## Sélection de texte (Visual mode)

- `v`: Activer le mode Visual pour sélectionner du texte caractère par caractère.
- `V`: Activer le mode Visual pour sélectionner des lignes entières.
- `Ctrl + v`: Activer le mode Visual block pour sélectionner des blocs rectangulaires.

## Enregistrement et exécution de macros

- `q<lettre>`: Commencer à enregistrer une macro dans la lettre spécifiée.
- `q`: Arrêter l'enregistrement de la macro.
- `@<lettre>`: Exécuter la macro enregistrée dans la lettre spécifiée.

## Recherche et remplacement

- `/<mot-clé>`: Rechercher le mot-clé vers l'avant.
- `?<mot-clé>`: Rechercher le mot-clé vers l'arrière.
- `n`: Passer à la prochaine occurrence du mot-clé.
- `N`: Passer à l'occurrence précédente du mot-clé.
- `:%s/<mot-clé>/<remplacement>/g`: Remplacer toutes les occurrences du mot-clé par le remplacement dans le fichier entier.

## Enregistrer et quitter

- `:w`: Enregistrer les modifications apportées au fichier.
- `:q`: Quitter Vim.
- `:q!`: Quitter Vim sans enregistrer les modifications.
- `:wq`: Enregistrer les modifications et quitter Vim.
