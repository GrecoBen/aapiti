# aapiti
logiciel de préparation de planches apéritives et devis 

# Installation du projet

-git clone du SSH comme d'habitude

-création d'un fichier .env.local avec base de données (voir exemple dans le .env)

-taper les commandes suivantes:

- `composer update` 
- `php bin/console doctrine:database:create` pour créer la base de données
- `php bin/console doctrine:migration:migrate` pour exécuter la dernière migration et créer les tables avec les relations adéquates

