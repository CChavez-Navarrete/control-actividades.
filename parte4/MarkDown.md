# Parte 4. Conceptos

## 1. Diferencia entre Git y GitHub
- **Git**: es un sistema de control de versiones, gestiona el historial de cambios en los archivos de un proyecto
- **GitHub**: es una plataforma en la nube que guarda los repositorios Git 

## 2. ¿Para qué sirve .gitignore?
El archivo **.gitignore** indica a Git qué archivos o carpetas no deben ser subidos al repositorio

## 3. ¿Por qué .venv no debe almacenarse en GitHub?
La carpeta **.venv** No debe subirse porque:
- Ocupa mucho espacio
- Puede variar según el sistema operativo

## 4. ¿Para qué sirve requirements.txt?
El archivo **requirements.txt** lista las dependencias necesarias del proyecto
Permite que otros desarrolladores instalen las mismas librerías con el comando
**pip install -r requirements.txt**
