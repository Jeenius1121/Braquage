# Braquage

Jeu de gestion de braquage : avec un budget limité, recrute ton équipe et achète ton matériel parmi des offres tirées au hasard, puis regarde le coup se dérouler. Il peut réussir, rater, ou finir entre les deux. Avec l'argent gagné, tu enchaînes des coups de plus en plus gros, de l'épicerie de village jusqu'à la réserve d'or.

Tout le jeu tient dans un seul fichier : `index.html`. Pour jouer en local, il suffit de l'ouvrir dans un navigateur. La partie est sauvegardée dans le navigateur.

Tout est généré au hasard : noms, passés, réputations, prix, lieux. Chaque recrue a un vrai niveau caché, et son dossier (antécédents, réputation, rumeurs) en découle. Son prix suit son niveau la plupart du temps, avec des bonnes affaires et des arnaques. Le vrai niveau est révélé dans le bilan.

La version du jeu est dans `index.html` (`VERSION`) et dans `version.json` : les deux doivent toujours avoir le même numéro. La page compare sa version avec `version.json` en ligne et affiche un bandeau « Mettre à jour » quand une nouvelle version est publiée.
