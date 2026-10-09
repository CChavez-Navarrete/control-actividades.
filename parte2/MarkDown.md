1. **Fork** Crear una copia del repositorio en tu cuenta de GitHub para poder trabajar sin afectar el original

2. **Clone** Descargar el repositorio (fork) a la computadora para trabajar localmente  

3. **Branch** Crear una rama para aislar los cambios y mantener la rama principal intacta

4. **Modificar archivos** Realizar los cambios necesarios en el código

5. **Commit** Guardar los cambios en el repositorio local 

6. **Push** Sube los commits de tu rama al fork   
7. **Pull Request (PR)** Solicita que tus cambios se integren al repositorio original 
8. **Review** El propietario revisa el pull request, se pueden pedir camios antes de agregarlo al proyecto origunal

9. **Request Changes** El propietario solicita modificaciones antes de aceptar

10. **Merge** Una vez aprobado, los cambios se integran al proyecto original  

11. **Sync Fork** maintiene tu fork actualizado con el repositorio original


## 2. Fork y Clone
“Clone crea una copia del proyecto dentro de mi cuenta de GitHub” es **incorrecta**

**Fork**: crea una copia del repositorio original en tu cuenta de GitHub  
**Clone**: descarga el repositorio a la computadora


## 3. Pull Request
Después de realizar **Fork, Clone, Branch, Modificar, Commit y Push**, los cambios **no forman parte del repositorio original todavía**.  
Para que se incorporen, debe hacerse un **Pull Request** y el propietario debe **aceptarlo y hacer Merge**


## 4. Request Changes
Si el propietario selecciona **Request Changes** en el Pull Request:  
- Debes modificar los archivos en tu rama local  
- Haces **commit** y luego **push** nuevamente  
- No se necesita crear otro Pull Request, el existente se actualiza automáticamente con los nuevos cambios


## 5. Merge y repositorio local
Cuando un Pull Request se acepta y se hace **Merge en GitHub**, el repositorio remoto se actualiza.  
El repositorio local del propietario no se actualiza automáticamente porque está en su computadora.  
El propietario debe ejecutar:  
- bash
**git pull origin main**

## 6. Sync Fork
Si el fork fue creado hace varios días y el repositorio original recibió nuevos commits

- la opción **Sync Fork** actualiza el repositorio en GitHub   
 
  - **Sync Fork** actualiza tu fork remoto en GitHub con los cambios del repositorio original  
  - **git pull** actualiza tu repositorio local trayendo los cambios desde el remoto   



