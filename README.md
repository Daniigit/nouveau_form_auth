# nouveau_form_auth
Dans cette nouvelle version on a:

integrer une base de donnees de MySQL
ajouter la création d'un compte
ajouter un bouton reset de remise a zero des champs 

# information technique
Le fichier "base_donnee" creer la base de donnee qui contient une table "eleve" ;
cette table contient 4 enregistrement 
## test de validité du formulaire
un premier element a pour username Conte et password alpha , un deuxieme element a pour username Emile et password beta ,

## test de Robustesse
Les deux autres element pourront etre utilisé pour tester la robustesse de notre formulaire 

# Detail sur l'utilisation du formulaire
Voici un script pour créer un formulaire d'authentification.

vous démarrez le serveur Appach et MySQL  sur XAMPP vous placez les fichiers dans un répertoire sur le serveur vous ouvrez une fenetre de votre navigateur

et vous tapez localhost/nom_repertoire

une fenetre doit s'ouvrir sur les  fichiers que je viens de vous envoyer

vous cliquez sur le fichier login et vous entrez les éléments de connexion.

Si le Login ou le mot de passe est erronné vous verrez le message "Login ou mot de passe incorrect" Si tout est bon vous aurez le message:

Bienvenue "username" dans votre espace personnel Déconnexion

Si vous cliquez sur "Deconnexion" vous revenez à la page de login.
