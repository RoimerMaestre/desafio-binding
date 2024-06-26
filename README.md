# desafio-binding

## Descripción
Este proyecto es una aplicación simple de Vue.js que permite a los usuarios introducir información de una tarjeta y visualizarla en un formato de tarjeta estilizado. El formulario permite la entrada de datos como el título de la tarjeta, número de la tarjeta, fecha de expiración, propietario, y tipos de imagenes (chip y tipo de tarjeta).

## Estructura del Proyecto
<ul>
<li>App.vue: Componente principal que incluye el componente TarjetaDatos.</li>
<li>components/TarjetaDatos.vue: Componente que contiene el formulario y la vista de la tarjeta con los datos introducidos.</li>

</ul>

## Uso
Ingresar la información de la tarjeta en el formulario.
La tarjeta estilizada se actualizará automáticamente con los datos proporcionados.

Estructura del Código
Componente TarjetaDatos.vue
Este componente contiene:

Un formulario para ingresar los datos de la tarjeta.
La vista de la tarjeta que muestra los datos ingresados.

## dudas
En lo personal no supe hacer la ruta de la imagen, esta estaba de manera local. investigue y la solucion fue usar require(tenemos entendido que se se utiliza para incluir archivos estáticos, como imágenes, de manera que puedan ser gestionados por el sistema de módulos.), tuve duda porque hasta ahora se habia usado basicamente ../archivo/etc



## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
