#initialisation avec git

on crée un repository sur GitHub Sf_Ecoride 
on crée le dossier local sous nom SF_Ecoride  à l'aide de la ligne de commande :
symfony new SF_Ecoride --version="7.3.x"
ona a ouvert le terminal dans ce dossier et executé :
git remote add origin https://github.com/Rihabdel/Sf_Ecoride.git
git branch -M main
git push -u origin main

#INSALLER DOCTRINE

l’ORM Symfony Pack contient toutes les librairies nécessaires de Doctrine propres à Symfony :
composer require symfony/orm-pack
Cela nous aidera notamment à créer nos entités Doctrine (nos tables), et plus encore !
composer require --dev symfony/maker-bundle
une fois installé les deux composants
le projet est à jour avec la commande suivante :
composer update

Ensuite dans le fichier .env, il va falloir configurer votre connexion à la base de données en personnalisant vos paramètres dans la variable d'environnement DATABASE_URL.
