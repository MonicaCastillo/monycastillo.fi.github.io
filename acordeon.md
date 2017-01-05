
#Acordeon Git
### $git init
    -inicializa un repositorio
### $git status
    -Muestra el estado actual de nuestro repositorio, permite saber si el repositorio contiene archivos de seguimineto, o si estan listos para estar registrados.
### $git add <archivo> | -A
    Este comando empieza a seguir a uno o más archivos generando un nuevo estado de nuestro proyecto.
    la bandera -A agrega todos los archivos del repositorio
### $git commit [-m "descripcion"]
    Este comando registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio
    Por lo general este comando se usa con la bandera  -m y un pequeño texto que describa lo que hicimos.
    
### $git log
    Este comando nos muestra el historial de commits que hemos hecho en nuestro     proyecto 
    -La bandera --oneline muestra cada entrada en una sola linea
    -tambien es posible ver la historiqa de un solo archivo, pasando como           argumento el nombre de éste.
    
#### $.gitignore
    
    - Este archivo nos permite ignorar archivos o directorios los cuales no            queramos que entren en el seguimiento de nuestro repositorio.
        -nombres de archivos o carpetas
        -wildcards*
#### $git checkout

    - Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio

lleva como argumento el  id del commit o parte de.
#### $git revert

    - este comando nos permite revertir un cambio ya registrado, creando un nuevo commit
    lleva como argumento el id del commit a revertir
### $git reset

    Regresa al único estado guardado, borrando permanentemente cualquier cambio en el área de pruebas.
    
    -lleva la bandera --hard
### $git clean
    Borra permanentemente los archivos  NO seguidos
    -lleva la bandera -f
 
Branch

Una rama branch es, en pocas palabras, una linea independiente de trabajo, la cual no afecta a nuestra rama principal (master), sin embargo, tiene la capacidad

###$git branch
    Lista las ramas existentes en el repositorio
    - si se le agrega [<nombre>] de rama como argumento, se creará una rama con ese nombre
    
#### $git merge
    Este comando fusiona dos ramas, fusiona una rama objetivo con la rama donde     nos encontramos actualmente.
    -recibe como parámetro la rama objetivo
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    

