# Cómo resolver conflictos en Git con rebase o merge
Cuando se trabaja en equipo con Git, es común encontrarse con conflictos al fusionar ramas. Esto ocurre cuando dos o más personas realizan cambios en el mismo archivo al mismo tiempo. Afortunadamente, Git ofrece dos formas de resolver estos conflictos: mediante el uso de rebase o merge.

<br>

## Resolviendo conflictos con merge
Cuando se utiliza ``merge`` para fusionar dos ramas, Git creará un nuevo commit que combina los cambios de ambas ramas. Si hay conflictos, Git mostrará un mensaje de error y señalará los archivos en conflicto.

Para resolver los conflictos en un archivo, se debe editar el archivo y eliminar las marcas de conflicto (<<<<<<<, =======, y >>>>>>>). Luego, se deben guardar los cambios y hacer un commit.

Una vez que se han resuelto todos los conflictos, se puede finalizar la fusión con el comando ``git merge --continue``. Si se desea abortar la fusión, se puede utilizar el comando ``git merge --abort``.

<br>

## Resolviendo conflictos con rebase
Cuando se utiliza ``rebase`` para fusionar dos ramas, Git aplica los cambios de una rama en la otra rama en orden cronológico. Si hay conflictos, Git detendrá el proceso de rebase y solicitará al usuario que resuelva los conflictos manualmente.

Para resolver los conflictos en un archivo durante un rebase, se deben seguir los mismos pasos que en un merge: editar el archivo, eliminar las marcas de conflicto, guardar los cambios y hacer un commit.

Una vez que se han resuelto todos los conflictos, se puede continuar con el proceso de rebase utilizando el comando ``git rebase --continue``. Si se desea abortar el rebase, se puede utilizar el comando ``git rebase --abort``.

Es importante tener en cuenta que si se utiliza ``rebase`` para fusionar ramas, se estará reescribiendo el historial de commits de la rama que se está actualizando. Por lo tanto, es importante hacer un backup de la rama antes de realizar el rebase.

[Regresar](README.md)