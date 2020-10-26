# ANNULER UN COMMIT

Modifier en local :

    git reset --hard <ID>

Annule toutes les modifications **après** le commit/

    git reset --soft <ID>

Reviens au commit mais n'annule pas les modifications.

# Ajouter la modification au précédent commit

    git commit --amend

Sans modifier le message :

    git commit --amend --no-edit
