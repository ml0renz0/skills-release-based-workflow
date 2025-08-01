<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

</header>

<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Paso 4: Aplicar un *hotifx* a la rama *master*

_¡Buen trabajo añadiendo cambios en **Alien Invasion**!_ :smile:

### Realizar un hotfix sobre la rama `master`

Ya hemos liberado nuestra versión `v0.1.1` de _Alien Invasion_. Lamentablemente, si revisamos el juego veremos que tenemos algunos errores:

<p align="center">
  <img src="../../blob/curso/images/alien-invasion-bug.png" alt="Alien Invasion">
</p>

Necesitamos sacar un _hotfix_ que nos permita sacar una nueva versión arreglada donde el fondo del juego vuelva a ser negro.

### :keyboard: Actividad: abrir una PR de **_hotfix_** a master

Vamos a crear una PR comparando la rama ya existente `hotfix/game-background` con `master`.

1. [Abre una **nueva pull request**](../../compare/master...hotfix/game-background) con `base: master` y `compare: hotfix/game-background`.  
1. Asegúrate de que el título sea: **[HOTFIX] Arreglar color de fondo**.
1. Añade una descripción detallada. Por ejemplo:  
   ```
   ## Descripción:
   - Reparado color de fondo del juego.
   ```
1. Haz clic en **Create pull request**.
1. Fusiona la PR haciendo clic en **Merge pull request** y elimina la rama.
1. El flujo creará una nueva PR para alinear `develop` con `master` que se mergeará automáticamente.
1. Espera ~20 segundos a que terminen todos los flujos en la sección **[Actions](../../actions)** del repositorio. Al finalizar, debería haberse generado la release hotfix `v0.1.2` en **[Releases](../../releases)**
1. Actualiza esta página. [GitHub Actions](https://docs.github.com/es/actions) avanzará automáticamente al siguiente paso.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

</footer>
