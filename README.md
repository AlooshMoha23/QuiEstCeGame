QuiEstCe:

1) Hébergement dans le cloud (Heroku) :
Nous avons préparé le jeu pour qu’il puisse être déployé en ligne sur Heroku.
L’utilisateur doit suivre ces étapes pour mettre le jeu en ligne : 
a. Créez un compte sur Heroku.
b. Installez l’interface en ligne de commande Heroku (Heroku CLI) sur votre ordinateur.
c. Dans le répertoire du jeu, exécutez les commandes suivantes :     heroku login     heroku create nom-du-joueur     git push heroku master     heroku open
d. L’URL générée par Heroku vous permettra d’accéder au jeu en ligne.

2) Tester le jeu en local (localhost) :
Pour tester le jeu en local, suivez ces étapes :
a. Téléchargez Node.js si vous ne l’avez pas déjà sur votre ordinateur : Télécharger Node.js (Windows) ou installez-le via NVM (Ubuntu) avec la version 17.6.0.
b. Vérifiez que vous avez Node.js version 17.6.0 et npm version 8.5.1 en tapant node -v et npm -v.
c. Mettez npm à jour si nécessaire : npm install -g npm@latest (Ubuntu). b. Nous utilisons également SweetAlert2 pour gérer les alertes dans notre code JavaScript. Vous pouvez le télécharger avec la commande : npm install sweetalert2.
d. Une fois que vous avez téléchargé Node.js et SweetAlert2, placez-vous dans le répertoire du jeu et exécutez la commande : node server.
e. Vous verrez dans le terminal que le serveur écoute sur le port 3000, ce qui signifie que tout fonctionne correctement.
f. Ouvrez un navigateur et accédez au jeu en local via l’URL : http://127.0.0.1:3000/ (Windows) ou http://localhost:3000/ (Linux).
