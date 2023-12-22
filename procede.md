Git init 

## Création de la branche dev
Git branch dev
git branch 

## Recette pour 1 personne
git add recette.md
git status
git commit -m
git push origin main

## Pour 2 personne
git status ## mon fichier à été modifié 
git add recette.md
git commit -m
git push origin main

## pour 10 personne
git status ## modification
git add recette.md 
git commit -m 
git push origin main

## création de la branche malade et switch dedans 
git branch malade
git branch 
git switch malade

## rendre la recette impossible à boire
git add recette.md 
git commit -m
git push origin malade

## rendre la recette encore pire qu'avant

git add recette.md 
git commit -m
git push origin malade

## la personne ne viens pas on annule tout 
git log --oneline 
git reset --hard eb15e63
git push --force origin main 

## ajouter le fichier procedé.md 

git checkout dev
git 

