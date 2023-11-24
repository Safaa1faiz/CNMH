
## About lab-laravel-basic

Bienvenue dans le guide d'autoformation Laravel ! Ce document a été créé pour vous aider à apprendre Laravel, un framework PHP puissant et élégant pour le développement web.

## Objectif

L'objectif de cette autoformation est de vous familiariser avec les concepts de base de Laravel, de vous guider à travers la création d'une application simple, et de vous fournir des ressources pour approfondir vos connaissances.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les éléments suivants sur votre machine :

- [PHP](https://www.php.net/manual/en/install.php)
- [Composer](https://getcomposer.org/doc/00-intro.md#installation)
- [Node.js et npm](https://nodejs.org/)
- [Laravel](https://laravel.com/docs/8.x/installation)

## Création d'un Nouveau Projet Laravel

- Ouvrez votre terminal et exécutez la commande suivante pour créer un nouveau projet Laravel :
   ```bash
   composer create-project --prefer-dist laravel/laravel nom-du-projet

1. Naviguez vers le répertoire du projet :

 ```
 cd nom-du-projet
```
2. Copiez le fichier .env.example pour créer un fichier .env :
```
cp .env.example .env
```
3. Générez la clé d'application Laravel :
```
php artisan key:generate
```
### Lancement de l'Application

1. Utilisez la commande artisan pour démarrer le serveur de développement :
```
php artisan serve
```
2. Ouvrez votre navigateur et accédez à http://localhost:8000 pour voir votre application Laravel fraîchement créée.

## Exploration
- Structure du Projet : Laravel suit une structure MVC. Explorez les répertoires app, routes, et resources pour comprendre la répartition des fichiers.

- Routes : Définissez vos routes dans le fichier routes/web.php pour gérer les requêtes HTTP.

- Contrôleurs : Utilisez des contrôleurs pour organiser la logique de votre application. Créez-les avec la commande php artisan make:controller NomDuController.

- Base de Données : Configurez votre base de données dans le fichier .env et utilisez les migrations pour créer des tables.

## Ressources des chapitres essentiels

[Grafikart](https://grafikart.fr/tutoriels/blade-template-laravel-2117#autoplay)

[Documentation officielle de Laravel](https://laravel.com/docs/10.x)

## Ressources Supplémentaires

[Laracasts](https://laracasts.com/)

[Forums Laravel](https://laracasts.com/discuss)

## Contribuer

Si vous trouvez des erreurs ou souhaitez contribuer à l'amélioration de ce guide, n'hésitez pas à ouvrir une issue ou à créer une pull request sur GitHub.

**Bon codage avec Laravel !**
