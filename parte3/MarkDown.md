1. ## Analiza
**git status** muentra el estado de los archivos del proyecto si estan cargados o no 
**git add README.md** solo carga el archivo README papoder hacer un commid
**git commit -m "Actualiza documentación"** se carga los archivos anteriores en tu computadora
**git push** carga los archivos en GitHub

2. ## Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿? **falta realizar un commit con un mensaje descriptivo**
↓
git push

3. ## Caso B
Repositorio GitHub
↓
¿? **git clone**, porque permite descargar una copia completa del repositorio remoto a la computadora
↓
Repositorio local


4. ## Caso C
Repositorio remoto actualizado
↓
¿? **git pull**, porque permite traer los commits más recientes del remoto y fusionarlos en la rama local, manteniendo sincronizados ambos repositorios
↓
Repositorio local actualizado

