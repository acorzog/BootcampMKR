Las Ramas se utilizan para crear experimentos de lo que uno quiere hacer, sin modificar la principal.
Los comandos mas utilizados para la creación de estas son:
git status: para ver en qué rama nos encontramos p.e. On branch master
git branch: sirve para listar todas las ramas p.e. git branch -> *master -> rama-1 -> rama-2
git branch <nombre de la rama> : sirve para crear una nueva rama p.e. git branch carolina
git checkout <nombre de la rama>: sirve para ubicarnos en la rama que creamos
git checkout -b <nombre de la rama> : Es un atajo para crear la rama y pararse sobre ella
git branch -m <nuevo nombre>: estando ubicados en la rama este comando sirve para cambiar el nombre de la rama
git merge: Sirve para integrar los commits de una rama a otra, primero debemos ubicarnos sobre la rama principal y ejecutar el comando git merge seguido del nombre de la rama
git branch -d <nombre de la rama que quieres eliminar>: sirve para eliminar una rama que ha sido integrada en otra