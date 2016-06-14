# Scaffold Jekyll Empty - Gulp (Browser-Sync)

Después de instalar las dependencias con `$ npm install` hay que ejecutar
el comando `$ jekyll build` para hacer el primer complidao del sitio,
después (y el resto de veces) ya se puede ejecutar el comando `$ gulp`
para trabajar en el proyecto.

El comando `$ gulp` ejecuta los mismos procesos que el comando
`$ jekyll s` con una diferencia, el servidor local se monta con
*Browser-Sync*.

Hay una tarea *sass* para procesar el archivo `.css` compilado por Jekyll,
la tarea se ejecuta con el comando `$ gulp sass` y no está integrada en
el compilado, hay que ejecutarla después de detener el comando `$ gulp`

Después de descargar/clonar:

```

// Solo recien descargado/clonado

  // Primero instalar dependencias

  $ npm install

  // Compilar el proyecto

  $ jekyll b

// El resto de veces

  // Empezar a trabajar

  $ gulp

```

Y a diviertirse!!!
