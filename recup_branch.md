# J'ai "cassé" une branche locale : Comment récupérer une branche propre depuis le serveur distant ?

Il y a plusieurs manières de régler ce problème. Mais ça revient généralement à la même chose: effacer sa branche cassée, recréer une branche en local et reprendre la branche propre distante. Voici une première commande:

* git checkout -b nouvelle_branche_locale nom_local_du_dépôt_distant/nouvelle_branche

_(trouvé sur: https://www.le-fab-lab.com/git-depot-distant.html)_

La deuxième option est la suivante:

* git reset --hard origin/main

Cette option écrase les modifications locales et les remplace par le contenu distant.
