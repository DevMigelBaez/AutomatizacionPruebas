# Generador de casos de prueba ADD



[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

El generador de casos de prueba es un proyecto SOAPUI que consume la información directamente de la base de datos y tiene soporte masivo para la generación de causisticas. 
 Para ejecutar el proyecto debes seguir los siguientes pasos

  - Previamente registrar la lib sqljdbc42.jar en C:\Program Files (x86)\SmartBear\SoapUI-5.4.0\bin\ext
  - Abrir el proyecto ADD_TEST-soapui-project.xml en SOAPUI 5.4.0
  - Ejecutar el script Generacion_Devolucion.sql para la generación de los casos de prueba.
  - Ejecutar los casos de prueba en el SOAPUI
  - Para hacer seguimiento a tu procesamiento puedes usar el script Seguimiento.sql

### Configuración

Dentro del script groovy encontraras esta configuración.

```sh
com.microsoft.sqlserver.jdbc.SQLServerDriver
jdbc:sqlserver://server:1433;databaseName=database;user=user;password=pass
```










License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
