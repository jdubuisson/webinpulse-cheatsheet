



question:

 # Comment envoyer une branche locale sur un serveur?


réponse:
j'ai commencé par recuperer le fichier en tapant la commande git clone 
 
pour envoyer une branche locale sur le serveur il faut d'abord créer un fichier avec la commande 
touch et le nom du fichier en snakecase

puis  faire un git checkout -b le nom de mon dossier pour créer ma branche (send_branch)
La commande git checkout peut être utilisée pour créer des branches ou basculer entre elle 


ensuite  git push  
Git push est une autre commandes GIT de base. Un simple push envoie les modifications locales apportées à la branche principale associée  
sauf qu'un message d'erreur s'affiche car il n y a pas de branche amont pour cela on doit  faire la commande 
git push --upstream origin send-branch  j'ai du accepeter Julien d'abord une fois que j'avais compris ce que j'avais a faire j'ai fait des modifications avant d'envoyer ca sur mon serveur 
 

1 git chechkout -b le nom de ma branche (send-branch)
2 les modifications sur mon fichier avec toutes les commandes 
3 git status pour voir l'etat de mes modifs 
4 git add 
5 git commit avec le msg en anglais 
6 git push 
et apres ca un git pull request pour demander a julien de me mettre sur la branche master 

