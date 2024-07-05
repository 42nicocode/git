# GIT 

# Init du dépot 

git init 
Reinitialized existing Git repository in /Users/42-nico/Recette/.git/ 
--> ls -a

git remote add origin git@github.com:42nicocode/git.git    

git status 

git add $fichier1 $fichier2 $fichier3
git .

git restore --staged $fichier1 

git status 
git add . 
git commit 
git status
git log          |   git log / git show :: évolution d'un projet à l'aide des informations des log

git branch
git checkout 


# Rédaction commit

Titre 
Description
Revue de code 

# Rédaction commit

'''bash
git add . | $fichier
git commit -m "type :: titre de la description"
git push origin main
'''

# Création branch
'''bash 
git checkout -b $branch
'''

# fusion branch

git branch
git checkout main
git merge develop
git status

