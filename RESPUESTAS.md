## Trabajo Practico GitHub/GitLab

### *Cuestionario*: 

**1. ¿Qúe es git?**

Git es un sistema de control de versiones, es decir, es un sistema que controla y/o administra las distintas versiones de un proyecto. 

**2. ¿Por qué queremos utilizar git?**

Para poder controlar o modificar un proyecto que estamos haciendo en conjunto con otros programadores. 

**3. ¿Qué es el bash que instala git?**

Es similar a una consola pero con mejores funcionalidades. 

**4. Describa los estados (working directory, staging area, repository).**

*Git tiene 3 estados:*

**a.** Working directory: Es donde el usuario o programador va a estar trabajando con todos sus archivos. 

**b.** Staging area: Es donde el usuario o programador prepara los archivos para luego guardarlos.

**c.** Repository: Es donde se almacenan las distintas versiones de los archivos que el usuario necesite.  

**5. Describa el flujo para crear un nuevo repositorio git.**

Debemos ejecutar el comando `git init` para crear un nuevo repositorio git.

**6. Describa el flujo para agregar un archivo simple al repositorio.**

Debemos ejecutar el comando `git add` 'nombre del archivo'

**7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.**

Una vez que modificamos el archivo al ejecutar el comando `git status` nuestra consola nos dira que hay un archivo que ha sido modificado, para guardar los cambios debemos ejecutar el comando `git add` 'nombre del archivo'. Asi agregamos el archivo modificado al repositorio. 

**8. ¿Cómo hago para ignorar un archivo o carpeta?**

Debemos crear un archivo llamado: ".gitignore" . Dentro de ese archivo escribimos el nombre de la carpeta y/o archivo que deseamos ignorar. 

**9. Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.**

`git branch` es un comando que nos permite crear otras versiones de nuestro proyecto, y poder interacturar con una y/o otra de las mismas. 

Para crear un `git branch` tenemos que ejecutar el comando `git branch` en la consola de git, éste nos mostrará las versiones que tenemos de nuestro proyecto. Para crear una version simplemente escribimos `git branch login ` (suponiendo que la version que vamos a crear va a tener un login).

Para empezar a trabajar sobre la versión `git branch login` ejecutaremos el comando `git checkout login`. De esta forma podremos alterar el proyecto y solo modificará esta versión del mismo. 

**10. ¿Qué hago con `git add .`?**

Con `git add .` agregamos *todos* los archivos al repositorio.

**11. ¿Cómo cambiamos de un branch a otro?**

Para cambiar de un branch al otro debemos ejecutar el comando `git checkout` seguido del nombre de la version con la que quisieramos interactuar, por ejemplo, `git checkout master`. De esta forma cambiamos del branch anterior por el branch master. 

**12. Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre de archivo RESPUESTAS.md). Súbalo al repositorio.**