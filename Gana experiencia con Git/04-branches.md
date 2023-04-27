# Branches y Merge: una guía básica
En Git, un "branch" es simplemente una línea de desarrollo separada que permite trabajar en diferentes aspectos de un proyecto sin afectar la versión principal. Mientras que un "merge" es la acción de combinar dos o más líneas de desarrollo en una sola.

<br>
<br>

## ¿Qué es una branch?
Un branch se crea a partir de una rama existente y permite trabajar en una versión separada del proyecto. Esto significa que cualquier cambio realizado en el branch no afectará la versión principal del proyecto hasta que se realice un merge.

Los branches son útiles para trabajar en nuevas características o correcciones de errores sin afectar el código existente. Por ejemplo, si se está trabajando en una nueva función en una aplicación, se puede crear un branch para trabajar en ella sin afectar la versión principal de la aplicación. Una vez que la nueva función está completa y ha sido probada, se puede realizar un merge para incorporar los cambios al proyecto principal.

<br>
<br>

## ¿Cómo se crea un branch?
En Git, se puede crear un branch utilizando el comando ``git branch``. Por ejemplo, para crear un branch llamado "nueva-funcion", se puede utilizar el siguiente comando:

``git branch nueva-funcion``

Esto creará un nuevo branch llamado "nueva-funcion" a partir de la rama actual.

Para cambiar al nuevo branch, se puede utilizar el comando ``git checkout``. Por ejemplo:

``git checkout nueva-funcion``

Esto cambiará al branch "nueva-funcion" y permitirá trabajar en él.

Para crear una branch y posicionarse al mismo tiempo en la nueva branch se usa el siguiente commando:

``git checkout -b nueva-funcion``

Para eliminar una branch creada se usa el siguiente commando:

``git branch -d nueva-funcion``

<br>
<br>

## ¿Qué es un merge?

Un merge es la acción de combinar dos o más líneas de desarrollo en una sola. En Git, se puede realizar un merge utilizando el comando ``git merge``.

Por ejemplo, si se ha trabajado en un branch llamado "nueva-funcion" y se desea incorporar los cambios al proyecto principal, se puede realizar un merge utilizando el siguiente comando:

``git checkout main``

``git merge nueva-funcion``

Esto cambiará al branch principal ("main") y realizará un merge del branch "nueva-funcion" en él.

[Regresar](README.md)
