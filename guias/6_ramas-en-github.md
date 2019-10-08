# Ramas (o branches) en GitHub

![Volver al futuro, universos paralélos](/recursos/volver-al-futuro-ramas.jpeg)

Las ramas son líneas de cambios separadas.

Por defecto, nosotros usamos la rama "master". Esta es la rama principal del repositorio.

![Verificando rama master en GitHub](/recursos/verificando-rama-master.png)

Pero también podemos crear otras ramas, lo cual nos va a permitir crear una nueva linea de cambios, separada de la principal, disminuyendo la posibilidad de integrar un cambio erróneo o sin completar a la rama principal.

Empecemos.

## Pasos

### 1) Crear una rama

Por ahora solo tienen master, pero cuando seleccionan para fijarse los branches, pueden crear uno nuevo.

Solo tienen que poner en el buscador un nombre de una rama que no exista, y ya les da la opción para crear una rama con ese nombre.

![Creando nueva rama en GitHub](/recursos/creando-nueva-rama.png)

### 2) Verificando rama creada

Ahora si se fijan, en la selección se muestra otra rama, la que recién crearon.

![Verificando rama creada en GitHub](/recursos/nueva-rama-creada.png)

### 3) [Hacer un cambio](/guias/4_haciendo-un-cambio-en-github.md)

Es importante saber dónde estamos parados antes de hacer un cambio, ya que el cambio que hagamos solo va a tener efecto en la rama donde estemos posicionados.

Una vez que agreguen un cambio, sigan con el paso 4.

### 4) Verificar cambio

Ahora, si vamos a "commits" (cambios).

![Ir a commits en GitHub](/recursos/ir-a-commits.png)

Vemos que se muestra el cambio (commit) que recién agregamos.

Pero si nos movemos a la rama principal de nuevo y revisamos los cambios, ahora no lo tenemos.

Eso se debe a que el cambio, solo se subió a la rama que creamos.

![Página commits en rama nueva en GitHub](/recursos/pagina-commits-rama-nueva.png)

Pero si volvemos a la rama "master" y nos fijamos los commits, no vamos a encontrar el último cambio. Ya que ese cambio se agregó a la rama nueva.

![Viendo commits en master en GitHub](/recursos/pagina-commits-master.png)

### 5) Integrando la rama con la principal

Tienen algunas opciones.

![Opciones hacer Pull Request en GitHub](/recursos/opciones-hacer-pull-request.png)

Una forma fácil, es hacer un Pull Request en su repositorio, comparando las 2 ramas. Como base "master" y para comparar su rama nueva. Pueden ir por cualquiera de las 3 opciones.

![Mergear Pull Request en GitHub](/recursos/mergear-pull-request.png)

Y si los cambios están bien, le dan "merge".

### Listo 🎉

Ahora si se fijan los commits de master, tienen el commit que hicieron en la nueva rama.

Como ya tienen todos los cambios de la nueva rama en master, ahora pueden eliminarla sin problemas, para eso tienen que ir a "branches".

En la práctica las ramas suelen usarse para subir cambios en paralelo a la rama master. Por ejemplo para una página web, se podrían estar subiendo cambios a una rama "

---

Para seguir pueden ver esta [guía de cómo manejarse con Git y GitHub](https://github.com/normanperrin/introduccion-a-git-y-github).
