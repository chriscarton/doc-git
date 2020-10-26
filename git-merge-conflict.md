# Résoudre les conflits

Quand on a modifié le master après avoir créer une nouvelle branche, **git merge** ne fonctionne pas.

# Trouver le fichier

    git status

# Trouver la différence

    git diff app/views/pages/contact.html.erb

# Ouvrir les fichiers

    <<<<<<<
        Ce qu'il y a au niveau de la branche master
    =======
        Ce qu'il y a au niveau de l'autre branche

Supprimer ce qu'on ne veut plus.

# Continuer

    Git add .

    git commit -m "Fix merge conflict"
