# 🚀 Subir Archivos a un Repositorio Diferente en GitHub desde VS Code
- Este documento te guía paso a paso para subir un archivo o proyecto a un repositorio diferente en GitHub usando VS Code y CMD. 
## 🛠️ Requisitos Previos
- Tener instalado Git
- Tener una cuenta en GitHub
- Tener VS Code instalado
- Verifica que Git esté instalado con: 
`git --version` 

## 📂 1. Abrir la Carpeta del Proyecto
Abre la carpeta donde está el archivo que quieres subir:
- VS Code > File > Open Folder

## 🔧 2. Inicializar Git
En la terminal de VS Code o CMD: 
`git init` 

## 📥 3. Agregar el Archivo
Agrega el archivo específico: 
`git add nombre_del_archivo`  
O para agregar todos los archivos: 
`git add .` 
## 📝 4. Hacer un Commit 
Realiza un commit de los cambios:
`git commit -m "Mensaje del commit"` 
## 🌐 5. Crear un Nuevo Repositorio en GitHub 
1. Ve a GitHub
2. Crea un nuevo repositorio
3. Copia la URL del repositorio (ejemplo: https://github.com/tuusuario/nuevo-repo.git) 
## 🔗 6. Vincular el Repositorio Local con el Remoto
En la terminal de VS Code o CMD:
`git remote add origin URL_DEL_REPOSITORIO` 
`git remote add origin https://github.com/tuusuario/nuevo-repo.git` 
## 🚀 7. Subir los Cambios al Repositorio Remoto
Para subir los cambios al repositorio remoto, utiliza el siguiente comando:
`git push -u origin main`  
## 🧠 Comandos Útiles
Comando	Descripción
`git remote -v`	Verifica los repositorios remotos
`git remote set-url origin URL`	Cambia la URL del repositorio remoto
