# Clonando un repositorio en GitHub

Si queremos modificar el contenido de un repositorio de otro usuario, no podemos hacerlo directamente. Tendrías que clonarnos su repositorio a nuestra cuenta, así desde nuestra cuenta estamos autorizados a hacerle cambios.

Al clonar un repositorio, vamos a tener una copia del repositorio público que elijamos en nuestra cuenta de GitHub. Recordar dos conceptos importantes para entender el funcionamiento de Github:

FORK: nos permitirá tener una copia exacta del proyecto con el cual queremos interactuar en nuestro repositorio REMOTO. Es decir, que una vez que hago el FORK dentro de mi repositorio 'remoto' tendré una copia del mismo.

CLONE OR DOWNLOAD: nos permitirá tener una copia exacta del proyecto de manera 'FÍSICA' en nuestra pc. Es decir, que clonando 'POR CONSOLA' el proyecto que nos interesa tendremos una copia exacta del mismo con el cual podemos interactuar abriendo el proyecto en nuestro editor agregando los cambios que quisieramos.

Entonces que debo hacer?
Lo que comunmente hago es hacer primero el FORK para hacer cambios en un proyecto, si los cambios se pueden agregar editando el archivo que me interesa lo hago en esta instancia, hago el COMMIT correspondiente seguido del PULL REQUEST. 
Si los cambios son varios y me interesa interactuar bastante con el proyecto, después del FORK, lo descargo en mi pc. Para clonarlo copio la url que me aparece cuando hacemos click en CLONE OR DOWNLOAD, abro la consola y voy al lugar donde quiero descargar el proyecto, y lo clono. Los comandos son:
Para clonarlo 'físicamente': git clone <url del proyecto de github>.

Ahora ya tenemos el proyecto en nuestra PC. Podemos hacer un branch para crear cambios y después unirlos con el master. Paso a paso, lo veremos más adelante.

## Pasos para clonar un proyecto en nuestro repositorio 'REMOTO'.

### 0) Crearse una cuenta de GitHub

### 1) Elegir repositorio a clonar

![Repositorio GitHub](/recursos/repositorio.png)

### 2) Clonarlo usando FORK

![Clonando repositorio GitHub](/recursos/clonar.png)

### 3) Elegir cuenta a la cual clonarlo.

![Eligiendo cuenta a la cual clonar repositorio GitHub](/recursos/elegir-cuenta.png)

### Listo

Ya tenemos el repositorio clonado en nuestra cuenta! 🎉

Ahora le podemos hacer modificaciones sin problemas, ya que está en nuestra cuenta.

![Repositorio clonado en GitHub](/recursos/repositorio-clonado.png)

---

Ahora que tenemos el repo en nuestra cuenta, podemos [hacerle cambios](/guias/4_haciendo-cambios-en-github.md).
