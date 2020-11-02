# Hello IoT

Autora: Sofia Pennella

## Introduccion

Este proyecto se hizo con el fin de transmitir la informacion recopilada por Agustin Bassi sobre Internet de las Cosas. Los articulos presentados forman parte de la bibliografia del  1° posgrado en Internet de las Cosas (CEIoT) en el cual es docente. De esta forma, el sitio web fue pensado tambien como una manera simple y atractiva de compartir estos conocimientos con sus alumnos.
Asimismo, contiene los enlaces a los distintos repositorios y proyectos de codigo abierto realizados por Agustin, apuntando a formar una comunidad de personas que los utilicen y los mejoren.

## Implementacion del proyecto

Este proyecto fue realizado en HTML y CSS utilizando las siguientes tecnologías/herramientas:

* Creacion de diferentes archivos de SCSS haciendo uso luego del @import en uno solo para unirlos.
* Utilizacion del framework Material Design for Bootstrap, aprovechando los estilos y animaciones de Material Design y las ventajas del sistema de cuadricula responsive que provee Bootstrap.
* Git como un software de control de versiones.

Los archivos .js son unicamente para correr el framework y para animaciones especificas.

## Estructura de directorios

La estructura de todo el proyecto se describe en de la siguiente forma.

```sh
├── images
├── index.html
├── mdb
│   ├── css
│   ├── img
│   ├── js
│   ├── scss
│   └── src
├── pages
│   ├── about.html
│   ├── acknowledgment.html
│   ├── articles.html
│   ├── collaborate.html
│   ├── posts
│   └── projects.html
├── README.md
├── scripts
│   ├── animations.js
│   └── utils.js
└── styles
    ├── elements
    ├── styles.css
    ├── styles.css.map
    └── styles.scss
```

## Instalacion de dependencias

Para correr este proyecto se necesita instalar el plugin Live Sass Compiler en Visual Studio Code.
Esta extensión depende de otra que se llama Live Server, la cual ayuda a recargar el navegador en cada cambio que se guarda.
En el pie de página del Visual Studio Code, saldrá el botón para iniciar la compilación de los archivos Sass (Watch).


## Correr el sitio web

Para correr el sitio, basta con abrir en el navegador el index.html. 
Tambien se puede utilizar el plugin Live Server de VSC e ir viendo los cambios que se van realizando en el navegador.


## Desplegar el sitio web

Se utilizo el hosting gratuito provisto por 000webhost:

* Registrarse y verificar cuenta.
* Seleccionar como obejtivo crear pagina web.
* Atribuir nombre al sitio y generar una contraseña.
* En el administrador de archivos y en la carpeta public_html subir las carpetas y archivos del sitio web.
* Posicionarse sobre index.html y seleccionar en la barra de navegacion el icono view para visualizar el sitio y obtener el link.


## Licencia

Copyright Sofia Pennella - 2020