Symfony UPR Distribution
===========================

Esta distribución de Symfony viene preconfigurada con un diverso conjunto de bundles para los estudiantes de la asignatura Programación Web Avanzada que se imparte en la Universidad de Pinar del Río, Cuba.

La idea es permitirles configurar y cargar estos bundles de marena rápida y sencilla.

Solo debes descargar y descomprimir el archivo `symfony-upr-distribution.tar.gz`:

    [url]

Ahora edita el fichero `app/config/parameters.yml` con los parametros de conexión a la base de datos y ejecuta:

    php app/console doctrine:migrations:migrate

Ahora pueden loguearse en el panel de administración /admin/dashboard con el usuario 'demo' y la contraseña 'demo'.

Enjoy!