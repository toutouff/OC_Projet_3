***connexion***

**tasks :**

page de connexion : création de la pages permettant de se créer un compte

page de connexion : connexion avec redirection sur la page d'accueil 

**User Stories et Scénario :**

je suis un tuteur/élève et souhaite me connecter a mon compte pour utiliser les fonctionnalité de la web app

Scénario  : connexion au site

Étant  donné que je suis un utilisateur inscrit 
quand j’accede  au site 
et que je remplis le champs adresse mail 
et que je remplis le champs mots de passe 
et que je clique sur le bouton intitulé "connexion"
si mes identifiant sont valide 
alors je suis connecté 
et redirige vers le tableau de bord 
sinon si mes identifiant ne sont pas valide 
alors je reste sur la page de connexion 
et une boite de dialogue affiche "identifiant invalide"

je suis un nouvelle utilisateur et souhaite me créer un compte pour accéder au fonctionnalité du site

scenario : creation dun compte 

etant donner que je ne suis pas un utilisateur inscrit ,ni connecté 
quand j'accede a la page s'inscrire 
et que je remplis le formulaire de connexion 
et que je clique sur le bouton inscription 
si mes identifiant remplisse les conditions d'inscription (complexité du mots de passe adresse mail valide et sans texte injurieux ou offensant)
alors un email est envoyé a ladresse du compte 
quand je clique sur le lien de confirmation 
alors mon compte est creer 
et je suis rediriger vers la page de connexion 
Sinon si mes identifiant ne remplisse pas les condition d'inscription 
alors une boite de dialogue affiche "veuillez vous assurer que vos identifiant remplisse les condition d’inscription ci dessous : "
et je reste sur la page d'inscription 
