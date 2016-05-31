# cloud
EUD
# Proyectos-Web-EuropeanValley
Bienvenido a EuropeanValley Development

# Developer Workspace


FROM [codenvy/php](https://hub.docker.com/r/codenvy/php/)

# Commands to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Arrancar Servidor Web, tail logs | `sudo service apache2 start && sudo tail -f /var/log/apache2/access.log -f /var/log/apache2/error.log` |
| 2      | Parar Servidor Web      |   `sudo service apache2 stop` |
| 3      | Reiniciar Servidor Web      |    `sudo service apache2 restart` |
| 4     | Arrancar Base de Datos  | `sudo service mysqld start`

# Vista Previa de los proyectos

code.europeanvalley.es:$mappedPort/$projectName
