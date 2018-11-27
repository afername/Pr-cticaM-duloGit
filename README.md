Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1. Para volver al commit de la posición anterior a la que está el HEAD en tras el último commit, descartando los últimos cambios y borrándolos del staging area

¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reset . Para devolver el HEAD al commit anterior y recuperar el estado previo

El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No. Master está ya contenida en styled. Aunque la absorba, se queda igual

El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Hay conflicto porque el archivo git_nuestro.md es distinto en htmlify

El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

Si, porque el archivo en styled estaba como en htmlify, pero en master todavía no

¿Qué comando o comandos utilizaste en el paso 25?
Git log --graph

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, porque al crear la rama title el HEAD está en el último commit, y si master absorbe a title, se puede poner en su posición. El archivo git_nuestro.md en title tiene un título que master no tiene.

¿Qué comando o comandos utilizaste en el paso 27?
Git checkout (al commit antes del merge)

¿Qué comando o comandos utilizaste en el paso 28?
Git reset HEAD git_nuestro.md

¿Qué comando o comandos utilizaste en el paso 29?
Git branch –D title

¿Qué comando o comandos utilizaste en el paso 30?
Add, commit, branch title, checkout

¿Qué comando o comandos usaste en el paso 32?
Git checkout

¿Qué comando o comandos usaste en el punto 33?
Git checkout <último commit>
