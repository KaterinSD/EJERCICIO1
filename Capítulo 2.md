1. Se crea las llaves SSH
 2. Crear un repositorio remoto o clonar el repositorio:
     - git clone ssh://user@host/path/to/repo.git 
 3. hacer cambios al Staging Area
 4. Hacer un commit:
     - git add . 
     - git commit -m "descripción de los cambios"
     - git status: muestra el estado del repositorio 
5. Envío los cambios al repositorio remoto:
     - git push -u origin nombre de la rama
6. Bajar los cambios del repositorio
    - Moverse a la rama de donde provienen los cambios 
    - git pull