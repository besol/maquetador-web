Prueba de Selección para Maquetador Web
==============

Enhorabuena! Desde Besol hemos visto tu potencial y ahora queremos ver si eres capaz de superar este pequeño 
reto que te hemos puesto por delante. La idea es bastante simple: maquetar la siguiente web utilizando HAML y Compass.

![Look and Feal](https://github.com/besol/maquetador-web/raw/master/public/images/pickdew.png)

Las únicas imágenes que puedes utilizar son las que se encuentran en la carpeta **public/images**. Dentro de
esa misma carpeta os podéis encontrar un fichero PSD en donde se puede ver con mayor detalle el grid layout. Todo lo demas (degradados, 
sombras, curvaturas, ...) debes hacerlo con funcionalidades de Compass.

Para esta prueba solamente vas a tener que trabajar con dos ficheros:

* **app/views/prueba/index.html.haml** Fichero que contiene el layout de la pagina en HAML
* **app/assets/stylesheets/prueba.css.scss** Fichero que contiene la hoja de estilo con funcionalidades de Compass

La prueba es opcional y tiene por objeto que tengamos una base para poder ver rápidamente en la entrevista como sería trabajar contigo.

Procedimiento de Instalación del Entorno
---------------------

En primer lugar tenéis que instalaros en vuestro equipo Ruby on Rails y Git. Podeis seguir los procedimientos de los siguientes enlaces:
* [How to Install Ruby on Rails](http://rubyonrails.org/download/)
* [How to install Git](https://help.github.com/articles/set-up-git)

Una vez instalado el entorno de Ruby on Rails y de Git, ejecuta los siguientes comandos desde una terminal
para descargarte este codigo e instalar las dependencias del proyecto.

	git clone git@github.com:besol/maquetador-web.git
	cd maquetador-web
	bundle install
	
Levantar el entorno
---------------------
Para levantar el entorno abre una terminal y ejecuta el siguiente comando:

	rails server

Conectate con tu navegador web a la URL http://0.0.0.0:3000

Una vez hecho eso puedes modificar los fichero HAML y COMPASS sin tener que arrancar y apagar el servidor cada dos 
por tres.

Procedimiento de Entrega
---------------------
Una vez completada la prueba, comprime la carpeta y mándanosla por correo a rrhh_arroba_besol_es antes del día 6 de agosto.

Documentación de Referencia
---------------------
* [Haml Reference Documentation](http://haml.info/docs/yardoc/file.HAML_REFERENCE.html)
* [Sass Reference Documentation](http://sass-lang.com/)
* [Compass Reference Documentation](http://compass-style.org/reference/compass/)





