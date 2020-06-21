# e-commerce

e-commerce with Symfony 4

Repository After cloning this, modify the .env file and replace the line below with your access to the database

```sh
DATABASE_URL=mysql://root:root@127.0.0.1:3306/masuperagence
```

To install the different packages necessary for the application to work
```sh
$ composer install
```

Run the php server
```sh
$ php bin/console server:run
```

Make the migration
```sh
$ php bin/console doctrine:migrations:migrate
```

Generate the fixtures
```sh
$ php bin/console doctrine:fixtures:load --append
```

To access the administration, go to '/ admin' then enter the admin credentials admin:admin

