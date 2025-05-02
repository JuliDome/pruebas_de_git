"#Listas de comandos"
git init: Incializa un repositorio.
git status: Muestra el estado del repositorio.
git add EJEMPLO.ext: Agrega un archivo al commit en preparación.
git restore EJEMPLO.ext: Vuelve, a nivel local, a la versión previa a la que se le hizo add o que se haya eliminado el archivo (con limitaciones).
git commit -m "MENSAJE DE EJEMPLO": Deja un paquete de cambios listo para ser subido. Usar desspués de add.
git restore --staged EJEMPLO.ext: Elimina del commit los cambios acoplados.
git push origin master: Sube a tu repositorio controlado de forma remota (GitHub) los commits del repo "origin" en la rama o el branch "master" sin necesidad de entrar y meterlo de forma manual en su respectiva página. Usar después de commit.
git log: Muestra el historial de commits locales.
<<<<<<< HEAD
=======
git restore EJEMPLO.ext: Vuelve, a nivel local, a la versión previa a la que se le hizo add.
git commit -m "MENSAJE DE EJEMPLO": Deja un paquete de cambios listo para ser subido. Usar desspués de add.
git push origin master: Sube a tu repositorio controlado de forma remota (GitHub) el repo "origin" en la rama o el branch "master" sin necesidad de entrar y meterlo de forma manual en su respectiva página. Usar después de commit.
git log: Muestra el historial de commits locales.
>>>>>>> 78cba79642f8b64bd357d8307efbd86575f4d284
