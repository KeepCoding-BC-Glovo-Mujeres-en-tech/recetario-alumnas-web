# WEBos endiablados. El recetario web

Este es un repo de práctica para que las alumnas de la especialización web podamos practicar `git` y a trabajar con GitHub en modo colaborativo.

## Contribuciones

Para participar en este repositorio, escribe a [Clara](https://github.com/claraMirandaZ) por [Discord](https://discord.com/channels/1005086932998561815/1006149531408281691) o por el grupo, **indicándole tu usuario de GitHub**, para que te añada como colaboradora y puedas subir tu código.

Puedes ir viendo cómo va el recetario visitando el enlace en la sección _about_ o pinchando en el icono de los huevos:

<div align=center>
  <a href="https://keepcoding-bc-glovo-mujeres-en-tech.github.io/recetario-alumnas-web/">
    <img src="https://github.com/KeepCoding-BC-Glovo-Mujeres-en-tech/recetario-alumnas-web/blob/main/images/deviled-egg-icon.png" style=" width:75px"/>
    <img src="https://github.com/KeepCoding-BC-Glovo-Mujeres-en-tech/recetario-alumnas-web/blob/main/images/deviled-egg-icon.png" style=" width:75px"/>
    <img src="https://github.com/KeepCoding-BC-Glovo-Mujeres-en-tech/recetario-alumnas-web/blob/main/images/deviled-egg-icon.png" style=" width:75px"/>
  </a>
</div>

## Inicio

Si en el futuro añadimos JavaScript, para poder ejecutar la aplicación será necesario tener instalado [Node JS](https://nodejs.org/) e instalar las dependencias locales ejecutando este comando en la terminal `npm install`.

Una vez hemos instalado las dependencias, el proyecto se arrancará ejecutando `npm start`, que abrirá una ventana del navegador y mostrará la página web (como haría el plugin de VSCode _Live Server_).

De momento podemos omitir este paso, porque sólo vamos a utilizar `html` y `css` para simplificar el las cosas.

## Proceso

1. Abre VSCode y clónate el repo en tu _Madre de los repos_ 😉 con `git clone https://github.com/KeepCoding-BC-Glovo-Mujeres-en-tech/recetario-alumnas-web.git`. Verás que tiene una carpeta _images_, otra de estilos, un archivo _README_ y un `index.html`. La estructura principal ya está desarrollada.

2. Cuando quieras trabajar en el repo, empieza **SIEMPRE** haciendo `git pull`. Esto asegurará que te traes todos los cambios hechos por las compañeras antes que tú.

3. Crea una rama nueva con `git branch <nombre-de-tu-rama>` y siguiendo la estructura _rama-de-nombre_. Sitúate en esa rama con `git checkout <nombre-de-la-rama>`.

4. Edita el `html` siguiendo la estructura dada, poniéndole **clases propias** a tus elementos para ponerle un `css` a tu elección. Sobra decir que es imprescindible que tu receta tenga buena pinta.

5. Cuando hayas terminado, guarda los cambios y añádelos al _staging area_ con `git add <nombre del fichero>` o `git add -A` (para añadir todos los cambios de una vez).

6. Haz un commit con `git commit` que siga unas buenas prácticas:
- Que sea en inglés.
- Que comience con un verbo en infinitivo.
- Que sea descriptivo pero no excesivamente largo.
- Que tenga una descripción más larga, en caso de ser necesaria.

Por ejemplo, _Add new recipe_ o _Write the recipe of paella_.

7. Vuelve a hacer `git pull`, porque nunca se hace suficiente `git pull` antes de `git push` cuando se trabaja en equipo xD

8. Haz `git push`. Ya está subida tu receta a tu rama.

Ahora toca mergear.

## Merge

Existen numerosos [tutoriales](https://www.freecodecamp.org/espanol/news/la-guia-definitiva-para-git-merge-y-git-rebase/) para enseñarnos a mergear, [lo hemos visto en clase](https://plataforma.keepcoding.io/courses/13532/lectures/215372)... Pero ponerlo en práctica da algo de miedo. "¡No me quiero cargar nada!" Da igual. Para eso está este repo, para practicar y poder cargarnos cosas. Mejor que se rompa este repo que el proyecto final.
Recuerda que el merge ocurre en la rama en la que estemos posicionadas, por lo tanto, antes de mergear debemos volver a main con `git checkout main`. Y no olvides que los merges también son commits.

En modo rápido se puede resumir en dos acciones principales (tras haber creado una rama, escrito una receta y pusheado):
```
git checkout main
```

```
git merge <nombre-de-la-rama>
```
Pero el tema es que los merges pueden generar [conflictos](https://styde.net/ramas-y-resolucion-de-conflictos-en-git/), esto suele abortar la acción y pide que soluciones el problema manualmente, aceptando o rechazando los cambios que vienen. Puedes repasar esta parte revisando la [sección 10](https://plataforma.keepcoding.io/courses/13532/lectures/230695) del curso de [Alberto](https://github.com/kasappeal). Si estás en la terminal integrada de VSCode y hay conflictos, es posible que se abra el editor para que aceptes los cambios que desees. Léelos bien para no pisar el código de ninguna compañera y simplemente añadir tu receta a la lista, esto requiere práctica y para eso está este proyecto. Si no ves los cambios en el repositorio, quizá tengas que hacer `git push`.

### Disclaimer

- Esta web **NO** es responsive (para mantener el código lo más simple y corto posible, por el momento).

- Las instrucciones de este README se irán actualizando para mejorar la experiencia de usuaria.
