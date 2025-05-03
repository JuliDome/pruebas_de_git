"#Listas de comandos"
git init: Incializa un repositorio.
git status: Muestra el estado del repositorio.
git add EJEMPLO.ext: Agrega un archivo al commit en preparación.
git restore EJEMPLO.ext: Vuelve, a nivel local, a la versión previa a la que se le hizo add o que se haya eliminado el archivo (con limitaciones).
git commit -m "MENSAJE DE EJEMPLO": Deja un paquete de cambios listo para ser subido. Usar desspués de add.
git restore --staged EJEMPLO.ext: Elimina del commit los cambios acoplados.
git push origin master: Sube a tu repositorio controlado de forma remota (GitHub) los commits del repo "origin" en la rama o el branch "master" sin necesidad de entrar y meterlo de forma manual en su respectiva página. Usar después de commit.
git log: Muestra el historial de commits locales.
git branch: Muestra la rama en la que es está trabajando.
git branch RAMA: Crea una rama con el nombre ingresado.
git branch -m NOMBREVIEJO NOMBRENUEVO: Se le cambia el nombre a una rama.
git checkout RAMA: Cambia a la rama ingresada. Tiene que estar ya creada.
git checkout -b RAMA: Crea una rama y te mueve a la misma.
git checkout COMMITCODE: Cambia a la rama ingresada, siendo esta una que se hace automáticamente con respecto al commit que se encuentra en el log.
git checkout -- ARCHIVO: Descarta los cambios hechos sobre el archivo y se vuelve a la última versión commiteada del mismo.
git branch -d RAMA: Elimina la rama ingresada. Solo funciona si la rama no es la activa.
git diff RAMA1 RAMA2: Muestra las diferencias que tienen entre sí las ramas ingresadas. El orden importa.
git merge SALIDA LLEGADA: Fusiona los contenidos de la primera rama con respecto a los de la segunda. Para que funcione, hay que estar sobre la rama de llegada (después de haber commiteado los cambios sobre la rama de salida).