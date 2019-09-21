# Site-de-biens-immobiliers

Site de biens immobiliers  codez en Symfony 4

Après avoir clôné ce repository, modifiez le fichier .env et remplacer la ligne ci-dessous par votre accès à la base de données

```sh
DATABASE_URL=mysql://root:root@127.0.0.1:3306/masuperagence
```


Pour installer les différents packages nécessaire au fonctionnement de l'application
```sh
$ composer install
```

Lancez le serveur
```sh
$ php bin/console server:run
```

Générez les fixtures
```sh
$ php bin/console doctrine:fixtures:load --append
```

Pour accèder à l'administration, aller sur '/admin' puis rentrez les identifiants admin:admin

