#GIT

### 1. ¿Que es git?
Es un sistema de control de versiones que controla o administra las distintas versiones de un programa.
### 2. ¿Por que queremos utilizar git?
Git sirve para controlar un proyecto que va creciendo, y en el podemos cambiar archivos, modificar código y la configuración del mismo. Nos permite tener un listado de los cambios que se van haciendo. También se puede contribuir con múltiples desarrolladores desde cualquier parte del mundo.
Se trabaja con un repositorio de código y múltiples desarrolladores pueden alterar ese código.
### 3. ¿Qué es el bash que instala git?
 Es  un terminal,que nos permite trabajar en git,  es como una consola con mejores funcionalidades.
### 4. Describa los estados (working directory, staging area,repository )
**Working directory:** Es donde cada desarrollador trabaja con todos los archivos.
**Staging area:** Donde se agregan todos los archivos que se preparan para guardarlos.
**Repository:** Donde se guardan  los cambios ya elegidos.
### 5.Describa el flujo para crear un nuevo repositorio git.
1. Creamos una carpeta.
2. Agregamos  la carpeta en visual studio code.
3. Click derecho en la carpeta **git bash**
4. Abrimos Git bash (similar a la consola)
5. En la consola ingresamos el comando `cd` \<nombre de la carpeta>.
6. Luego ingresamos `git init` y ya tenemos inicializado el repositorio.
### 6. Describa el flujo para agregar un archivo simple al repositorio.
En la carpeta creada puedo crear archivos. Para agregar estos archivos  al repositorio,  en la terminal ingresamos el comando `git add` \<nombre archivo>. 
Para ver si el archivo esta agregado ingresamos `git status`.
### 7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.
 Si modificamos un archivo en Visual studio, lo guardamos y luego vamos a la terminal.
  + Ingresamos el comando `git status` que nos va a mostrar que el archivo fue modificado.
  + Luego ingresamos el comando `git add`< nombre archivo> para agregarlo y guardarlo en el  repositorio.
### 8. ¿Cómo hago para ignorar un archivo o carpeta?
Creamos un archivo con el nombre `.gitignore`, luego lo guardamos, y alli es donde vamos a colocar el nombre de las carpetas o archivos que queremos ignorar.
### 9. Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.
Un Branch es la rama master (un apuntador que se crea con la primer confirmacion de cambios que realicemos). En cada confirmacion de cambios la rama ira avanzando automaticamente. En estas ramas nuevas se copia todo el proyecto que vamos realizando, en ellas podemos realizar modificaciones, sin modificar el proyecto principal, ya que se genera por decirlo asi otra version del proyecto. Para agregar una rama nueva utilizamos el comando `git branch`. 


### 10. ¿Qué hago con `git add `?
Con el comando `git add` agrego un archivo al repositorio.
### 11. ¿Cómo cambiamos de un branch a otro?
Para cambiar de un branch a otro, utilizamos el comando `git checkout` \<nombre del branch>.



  




