ProjetJEE
=========

Réalisation d'un site de suivi de projets pour Junior-Entreprise

#####Installation de github :

Aller sur https://github.com/    
Créer un compte.   
Aller sur : http://help.github.com/linux-set-up-git/   
Suivre le tuto pr installer github et ajouter une clé SSH (il en faut une pour chaque PC duquel vous allez utiliser github).   
Envoyer moi votre login pour que je vous ajoute en collaborateur du projet JEE.

#####Utilisation de github :

cd ../LeDossierduProjetJEE   

######La première fois :    
git init   
git remote add origin git@github.com:tfonllad/ProjetJEE.git   
(ne pas remplacer mon login par le votre dans la commande ci-dessus).

######Pour récupérer la dernière version depuis le site      
git fetch origin   
git merge origin/master   

######Pour uploader sa version sur le site (une fois que je vous ai mis en collaborateur) :   
git commit -am 'commentaire'   
git push origin   


