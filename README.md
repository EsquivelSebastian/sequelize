# Autentificación con JWT y Sequelize

Un ejemplo o boilerplate de autorización basada en JWT y Sequelize ORM de JavaScript con Roles (admin, user...ect) y políticas. Obviando lo de Express, Node, Sequelize CLI, MySQL (al ser ORM puedes utilizar Postgre, MariaDB, SQLite).

## Mejoras posibles o problemas conocidos

* El seeder de roles da problemas cuando lo migras, habria que separarlo en dos diferentes.
* El archivo de routas es un desastre, es posible que sea una gran idea ordenarlo...
* Dentro de User model se puede añadir un metodo setter de Sequelize para encriptar la contraseña ahi y eliminarlo del auth.js middleware...

