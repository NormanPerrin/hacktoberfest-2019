# Git y GitHub

> Sistema de control de versiones, distribuido.

Si no entendieron la definición, sigan leyendo.

## Versionado

Podemos hacer un seguimiento de nuestros cambios en el proyecto, sabiendo quién hizo el cambio, qué se cambió, y cuándo. Permitiéndonos volver a versiones anteriores si queremos.

## Distribuido

Funcionamiento GitHub:

![Funcionamiento GitHub](/recursos/github-flow.png)

Para empezar, podemos definir a un **repositorio** como un directorio, puede contener archivos y otros directorios.

En esta imagen, podemos ver que Norman, Mariana y Josefina tienen una copia de un mismo repositorio en sus computadoras (también podrían hacerse una copia en su cuenta de GitHub).

Una vez copiado el repositorio a su cuenta o computadora, pueden modificar el contenido del mismo como quieran. Luego, pueden subir los cambios que hayan hecho al repositorio original, para que las otras personas trabajando en ese proyecto puedan acceder de una forma fácil a los cambios.

### Repositorio remoto

Es el repositorio que se usa como referente de todas las copias, al que se le subirían todas las mejoras, y del que se harían las copias.

Al trabajar cada uno localmente, para avisar de cambios a otras personas, todos suben sus cambios a un repositorio **central**, de esta forma, solo hay que tener conocimiento del repositorio central, y no de todas las otras copias que pueda haber.

Actualmente hay algunas plataformas, como GitHub, la cual nos permite crear estos repositorios.

### Repositorio local

Puede ser un repositorio que nos creamos en nuestra máquina, o un repositorio que nos descargamos.

Los cambios que les hagamos a esta descarga solo se van a ver reflejados en nuestra máquina, para actualizar el repositorio remoto con nuestros cambios, primero tenemos que estar autorizados para eso, luego tenemos que especificárselo.

Podemos crearnos un repositorio en nuestra máquina y nunca subirlo. Si no queremos compartirlo con otras personas y solo nos interesa tener un historial de nuestros cambios, entonces es totalmente válido.

### Juntando las partes

Entonces podemos decir que es distribuido porque se trabaja en distintas partes, el código, aunque centralizado en 1 lado, puede estar copiado en muchos otros. Si el día de mañana le pasa algo al servidor remoto, no hay de que preocuparse, ya que tenemos una copia.

---

Les recomiendo seguir con algo práctico: [Clonando un repositorio](/guias/3_clonando-un-repositorio-en-github.md).
