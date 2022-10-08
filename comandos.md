# Creación

git init 

--> Crea un repositorio local vacío en ek directorio actual.
Éste se almacena en el directorio .git 




git status 

--> Estes es el más usado de todos. Nos dice la rama en la que nos encontramos y los ficheros que contiene el stage junto a su estado (new/modified/deleted). Además avisa ficheros sin seguimiento por git.

(untracked) o ficheros con conflictos

Flujo entre working/stage/repo
git add <lista de ficheros> #Manda uno o varios ficheros separados por espacio o un directorio al estaging area. Recién añadido un nuevo dichero al repositorio, este se encuentra en estado "untracked" y debemos hacer un primer add. Podríamos usar el carater "." si queremos enviar todos los ficheros del directorio de trabajo que tienen algun cambio.

Tnbien admite comodines, ej: git add *js

git commit -m "descripcion breve" #Registra definitivamente los cambios que previamente estaban en el stage.