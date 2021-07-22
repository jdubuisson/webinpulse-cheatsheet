# Comment annuler des modifications locales non versionnées ?

**Scénario** : Le chat a traversé le clavier et a, d'une manière ou d'une autre enregistré les modifications, puis a fait planter l'éditeur. Cependant, vous n'avez pas validé ces modifications. Vous voulez tout annuler dans ce fichier et revenenir simplement à l'état dans lequel il se trouvait.

**Annuler avec :**  *"git checkout -- bad filename*


git checkout modifie les fichiers du répertoire de travail dans un état précédemment connu de Git.