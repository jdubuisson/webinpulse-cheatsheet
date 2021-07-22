# Comment récupérer les "nouveautés" du dépôt distant ?
Pour récupérer le contenu d'une nouvelle branche distante :
 - Soit fusionner avec la branche locale sur laquelle on travaille :
git merge nom_local_du_dépôt_distant/nouvelle_branche
 - Ou créer une branche locale basée sur le contenu de la branche distante :
git checkout -b nouvelle_branche_locale nom_local_du_dépôt_distant/nouvelle_branche
La nouvelle branche ainsi créée est une branche de suivi sur laquelle on peut lancer les commandes git push et git pull.