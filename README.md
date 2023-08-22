1. Se crea el repositorio en Github.
2. Clonar el repo de manera local con el comando `git clone "urlDelRepo"`.
3. crear un archivo dentro de la carpeta que se ha clonado y añadirlo al arbol con: `git add .` (para todos los archivos) , normalmente lo ideal sería hacerlo así, en caso contrario, pues se añade segun el nombre del archivo. 
4. Realizar el commit: `git commit -m "mensaje explicativo del commit."`
5. Realizar el push: `git push -u origin ramaDePreferencia` o `git push

   **NOTA:** Durante todo el proceso que vamos realizando, podemos usar el comando: `git status `para observar como se encuentra el arbol.

6. No es recomendado trabajar siempre en la rama principal, lo mejor es crear una nueva rama, para esto se puede usar el comando:
`git checkout -b rama-de-trabajo`

   ----> El comando: `cat "nombreDelArchivo"` nos permite observar el contenido del archivo deseado.
7. Una vez realizados los cambios deseados en la nueva rama, guardamos los cambios (**punto 3**) realizamos el commit **(punto 4)**

   --->Es importante saber como se encuentran nuestros commit, para ello podemos usar el comando: `git log`
8. Al estar seguro de todos los cambios que deseamos hacer, debemos proceder a unir los cambios de la nueva rama a principal, para ello podemos usar el comando: `git merge`

9. una vez realizado el push, nos podemos cambiar a la rama main ( `git checkout main` ) y traer los nuevos cambios del repositorio ( `git pull` ). 
10. El comando `git branch` nos permite revisar las diferentes ramas que tenemos. 
11. Para eliminar una rama específica, podemos usar el comando: `git branch -D "nombreDeLaRama"`
12. Si se  está  en una rama y se quieren  pasar los cambios directamente desde la rama x, a la rama principal usamos el comando: `git merge "nombreDeLaRamaDeLaCualQueremosTraerLosCambios"`
13. Descartar un commit: `git revert "idDelCommit"`
