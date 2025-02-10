#Commande git
>Liste des commandes git
## git init
- Permet d'initialiser un repertoire
## git add
- Permet d'ajouter un fichier pour des modifications dans le stagging

## git commit
- Permet d'enregistrer une modification en local
- Le message est important

## git push
- permet de pousser les modifications en ligne

## git status
- Permet de verifier le status du repertoire
- Permet de lister les modifications à traiter

## git log
- Permet de voir l'historique des modification

## git log --oneline
- Permet de voir l'historique resumé des modifications

## git branch
- Permet de créer une branche

## git checkout
- Permet de passer d'une branche à une autre
- Permet de se deplacer d'une branche à une autre
- Avec l'option -b checkout crée la branche si elle n'existe pas

## git pull
- Permet de recuperer les modifications distantes

## git rebase
- Permet de recuperer les modification dans la branche parente ou mère
- Les modification de la branche mère sont placées en dessous des modification de la branches courante
- Les modification de la branche courante sont placées au dessus des modification de la branches mère

## git merge
- Permet de recuperer les données de la branche fille(features/code-html) vers la branche parente (Main)

## git reset
- Permet de supprimer un commit
- Permet aussi de revernir à un commit défini par son identifiant
- Attention à utiliser avec précaution