# Respuesta del ejercicio.

1. ¿Que comando utilizaste en el paso 11? ¿Porque?
R: Utilice el comando git reset --hard HEAD~1, se pedia deshacer el
commit y que los cambios del working copy se deberian perder. Si fuese
que quisieramos conservar los cambios no usaria --hard.

2. ¿Que comando o comandos utilizaste en el paso 12? ¿Porque?
R: Utilice el comando git reflog para buscar el ID del commit que habia
creado en el paso 10 y luego utilice el comando git reset --hard con el
ID para rehacer el commit.

3. El merge del paso 13, ¿Causo algun conflicto? ¿Porque?
R: En la consola no mostro ningun conflicto, pero si un mensaje que
decia Already up to update, que el commit style ya estaba actualizado y la informacion que
esta en main ya esta en style.

4. El merge del paso 19, ¿Causo algun conflicto? ¿Porque?
R: Si causo conflicto, nos decia que un archivo en dos ramas diferentes
contenian informacion en una misma linea. Por lo tanto debia
solucionarlo. Lo solucione siguiendo las instrucciones de mantener el
contenido de la rama styled.

5. El merge del paso 21, ¿Causo algun conflicto? ¿Porque?
R: No en este merge no se produjo ningun conflicto. Se hizo un merge
fast-forward. Las ramas forma un lista.

6. ¿Que comando o comandos utilizaste en el paso 25?
R: git log --graph --decorate --pretty=oneline, tambien he
aprovechado para configurar un alias usando el siguiente
comando git config alias.graph "log --graph --decorate --pretty=oneline"
asi solo uso git graph y tengo un graph mas bonito.

7. El merge del paso 26, ¿Podria ser fast forward?
R: Si podria ser fast forward, porque ambas ramas forman una lista.

8. ¿Que comando o comandos utilizaste en el paso 27?
R: git reset HEAD~1

9. ¿Que comando o comandos utilizaste en el paso 28?
R: git restore git-nuestro.md

10. ¿Que comando o comandos utilizaste en el paso 29?
R: git branch -D title, al usar -d git nos avisa que un commit podria quedar
no accesible.

11. ¿Que comando o comandos utilizaste en el paso 30?
R: git reflog, git reset --hard 49b9ed5 el hash del commit.

12. ¿Que comando o comandos usaste en el paso 32?
R: git reflog, git checkout

13. ¿Que comando o comandos usaste en el paso 33?
R: git reflog, git checkout

## Alfredo Sánchez - @alfred3ks