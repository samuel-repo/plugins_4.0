# plugins_4.0

![alt text](https://castrinho8.github.io/akademy-startups-presentation/img/logos/empresas/redmine.png)

Plugins necesarios para redmine 4.0


Descargar e instalar redmine desde:
https://bitnami.com/stack/redmine/installer

Una vez instalado redmine, vamos a la siguiente ruta:
carpeta_raiz > \apps\redmine\htdocs\plugins

Una vez descargado el repositorio de plugins en la carpeta plugins de redmine, debemos de instalar, las gemas necesarias:
> bundle install

Los plugins necesitan una migración, asi que debido a eso se tiene que ejecutar el siguiente comando:
> bundle exec rake redmine:plugins:migrate RAILS_ENV=production

El comando se ejecuta desde la carpeta raiz de Rails, que en este caso el directorio htdocs
