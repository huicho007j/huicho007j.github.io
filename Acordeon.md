# Acordeón Git

### $ git init 
-Inicializa un nuevo repositorio

### $ git status
-Muestra estado actual de repositorio, saber si contiene archivos o si están listos para ser registrados

### $ git add
-Empieza a seguir a uno o más archivos y los agrega al área de preparación generando un nuevo estado de nuestro proyecto. La bandera -A agrega todos los archivos del repositorio

### $ git add <archivo> | -A
-Prepara un archivo para nuevas etapas

### $ git commit
-Registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio. Por lo general se usa con la bandera -m y un pequeño texto que describa lo que hicimos.

### $ git commit [-m "descripcion"]
-Guarda el nuevo estado en el historial del repositorio

### $ git log
-Muestra el historial de commits que hemos hecho en nuestro proyecto. La bandera --oneline muestra cada entrada en una sola línea. También es posible ver la historia de un sólo archivo, pasando como argumento el nombre de éste.

### $ git log [ --oneline <archivo>]
-Muestra el historial completo de commits del repo o de un archivo en específico.

### .gitignore
-Este archivo nos permite ignorar archivos o directorios (como los .exe o a.out de un programa) los cuales no queramos que entren en el seguimiento del repositorio.    -nombres de archivos o carpetas separados por saltos de línea    -wildcards*

### $ git checkout
-Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio. LLeva como argumento el id del commit o parte de.

### $ git revert
-Este comando nos permite revertir un cambio ya registrado creando un nuevo commit. Lleva como argumento el id del commit a revertir.

### $ git reset
-Regresa al último estado guardado borrando permanentemente cualquier cambio en el área de pruebas que se hiciera con add. Lleva la bandera --hard

### $ git clean
-Borra permanentemente los archivos no seguidos, es decir los que no se han agregado con add. LLeva la bandera -f.



