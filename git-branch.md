# LES BRANCHES

# Lister les branches

    git branch

Avec les derniers commits

    git branch -v

# Créer une nouvelle branche "refactoring"

    git checkout -b refactoring

**-b** permet de basculer automatiquement sur la branche

SINON faire :

    git branch refactoring
    git checkout refactoring

# Après avoir fait les modifications

    git add .

    git commit -m "changements sur la branche refactoring"

# Basculer sur le master

    git checkout master

# Fusionner

    git merge refactoring

# Supprimer la branche

    git branch -d refactoring

# Supprimer une branche (pas encore fusionnée)

    git branch -D refactoring
