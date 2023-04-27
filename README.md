# Application-Medicale-Groupe
 Application Laravel Comme Doctolib


## 1: Installation du projet sur votre PC

Clonez le git avec 
`git clone https://github.com/AvivoB/Application-Medicale-Groupe.git`

Entrez ensuite dans le projet avec :
`cd Application-Medicale-Groupe`

Tapez ensuite les commandes d'installation du projet
`composer install`
`npm install && npm run dev`

Créez ensuite la base de donnée du projet sur votre PC


Copiez et renommez le fichier .env.exemple en .env



Configurez le fichier .env qui se situe dans le dossier du projet comme ceci
`DB_DATABASE=VOTRE_BASE_DE_DONNEES`
`DB_USERNAME=UTILISATEUR_DE_VOTRE_BDD`
`DB_PASSWORD=MOT_DE_PASSE_DE_VOTRE_BDD`


Dans le terminal de commande lancez
`php artisan migrate:fresh --seed`

Si vous utilisez WAMP, allez sur le projet pour le voir
Si vous utilisez Laragon, un lien va etre créé
Et si vous n'avez ni WAMP, MAMP ou autre lancez a commande `php artisan serve`

## 2 : Développement
Afin de travailler sans conflit, il faut que chacun puisse se créer une branche sur le git et qu'a chaque modification il envoie son travail sur sa branche

FAITES ATTENTION ! Ne Pusher pas sur la branche des autre ni sur le Main ou Master !!!!!!!!!!!