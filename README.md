1. Crear el repo en github
2. Clonar el repo de manera local:
3. `git clone "urlDelRepo"`
4. crear un archivo dentro de la carpeta que se ha clonado y añadirlo al arbol con: `git add .` (para todos los archivos) o `git add "nombreDelArchivo"`
5. Realizar el commit: `git commit -m "mensaje explicativo del commit."`
6. Realizar el push: `git push -u origin ramaDePreferencia` o `git push

   **NOTA:** Durante todo el proceso que vamos realizando, podemos usar el comando: `git status `para observar como se encuentra nuestro arbol o stack.

   No es recomendado trabajar siempre en la rama principal, lo mejor es crear una nueva rama, para esto se puede usar el comando:
7. `git checkout -b rama-de-trabajo`

   El comando: `cat "nombreDelArchivo"` nos permite observar el contenido del archivo deseado.
8. Una vez realizados los cambios deseados en la nueva rama, guardamos los cambios (**punto 4**) realizamos el commit **(punto 5)**

   Es importante saber como se encuentran nuestros commit, para ello podemos usar el comando: `git log`
9. Al estar seguro de todos los cambios que deseamos hacer, debemos proceder a unir los cambios de la nueva rama a principal, para ello podemos usar el comando: `git merge`

10. una vez realizado el push, nos podemos cambiar a la rama main ( `git checkout main` ) y traer los nuevos cambios del repositorio ( `git pull` ). 
11. El comando `git branch` nos permite revisar las diferentes ramas que tenemos. 
12. Para eliminar una rama específica, podemos usar el comando: `git branch -D "nombreDeLaRama"`
