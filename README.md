
# Módulo 1: Ejercicio de evaluación final

En este repositorio se presenta el ejercicio de evaluación final de Elena Clemente Rentero para el primer módulo de maquetación empleando HTML y CSS del curso de desarrolladora front-end impartido por Adalab. 

## Enunciado

El ejercicio consiste en desarrollar una página web de acuerdo a un diseño dado. En la que hay que resolver varios puntos: 

- Usar Sass.
- Usar Flexbox y CSS Grid.
- Usar media queries.
- Resolver algunas interacciones usando transiciones.

## Maquetación

En primer lugar se debe realizar la maquetación sobre un diseño dado.

1. El botón de hamburguesa (en la esquina superior izquierda) debe estar fijo en la parte superior de la pantalla y **no** debe desaparecer al hacer scroll. El icono de la hamburguesa debe ser un enlace a la página de Adalab. Este menú de hamburguesa no desplega ningún submenú.
1. Primer módulo (Anonymous proxy): debe estar maquetado con **flexbox** y debe ocupar el alto de la ventana del navegador.
1. Segundo módulo (Looking Through A Window): se puede maquetar usando las propiedades de CSS que se deseen.
1. Tercer módulo (3 Reasons To Purchase): los 3 elementos del listado deben estar maquetados con **CSS Grid** en todos los tamaños de pantalla.
1. Cuarto módulo (footer): se debe maquetar usando **flexbox**. Todos los textos de la columna "ARTICLES" y todos los textos de la columna "TWITTER" deben ser enlaces a la página de Adalab.

## Interacción

En total, hay varias interacciones que resolver:

1. El botón de flecha del módulo hero debe enlazar a la sección "3 Reasons To Purchase".
1. El botón de flecha del footer debe enlazar al inicio de la página.
1. Todos los links del pie deben ir a https://adalab.es.
1. En el hover de los botones ("Go" y "3 Reasons To Purchase") se debe incluir una transform que dejamos a vuestra elección (BONUS-> hacer la transform con transition, investigar la propiedad transition)
1. BONUS: hacer una pequeña animación en el botón del footer.(investigar la propiedad animate )

## Guía de inicio rápido

Este proyecto se ha realizado utilizando una plantilla de proyecto con funcionalidades preinstaladas y preconfiguradas, como es el **Adalab web starter kit**. Este Kit incluye un motor de plantillas HTML, el preprocesador SASS y un servidor local y muchas cosas más. Para poder trabajar con él se debe tener previamente instalado Node JS. 

### Pasos a seguir cada vez que se quiere arrancar un proeycto desde cero: 

1. **Crea tu propio repositorio**.
1. Descarga el **Starter kit desde GitHub**.
1. **Copia todos los ficheros** en la carpeta raíz del repositorio.
1. **Abre una terminal e instala las dependencias** locales ejecutando en la terminal de comando: 

```npm install```

### Pasos para arrancar el proyecto:

Una vez hemos instalado las dependencias, **el proyecto debe arrancarse cada vez que nos pongamos a programar** ejecutando el siguiente comando:

```npm start```

Este comando: 

- **Abre una ventana de Chrome y muestra tu página web**.
- También **observa** todos los ficheros que hay dentro de la carpeta ```src/```, para mostrar los cambios cada vez que modifiques un fichero, **refrescando tu página en Chrome**. 
- También **procesa los ficheros** HTML, SASS/CSS y JS y los **genera y guarda en la carpeta** ```/public```. 

Después de ejecutar ```npm start``` ya puedes empezar a editar todos los ficheros que están dentro de la carpeta ```src/``` y programar cómodamente. 
