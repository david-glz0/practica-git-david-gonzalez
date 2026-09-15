# Práctica de Git y GitHub

* **Nombre completo:** David Franco González Barrón
* **Nombre de la práctica:** Creación y Sincronización de Repositorio Git
* **Objetivo:** Crear un repositorio local, vincularlo con GitHub y comprobar la sincronización bidireccional de cambios.

## Descripción del procedimiento realizado
1. Se creó la carpeta del proyecto local y se inicializó como repositorio Git.
2. Se configuró la rama principal como main y se crearon los archivos datos.txt y README.md.
3. Se realizó el primer commit local y se vinculó con un repositorio público en GitHub.
4. Se editó el archivo datos.txt desde la web de GitHub y se descargó el cambio a la computadora local.
5. Se modificó nuevamente el archivo localmente y se enviaron los cambios al remoto.

## Comandos de Git utilizados y su función
* git init: Inicializa una carpeta como repositorio local de Git.
* git branch -M main: Renombra la rama activa a main.
* git status: Muestra el estado actual de los archivos.
* git add .: Agrega todos los archivos al área de preparación (Staging Area).
* git commit -m "mensaje": Guarda los cambios en el historial local.
* git remote add origin URL: Vincula el repositorio local con un repositorio en GitHub.
* git remote -v: Muestra la URL del repositorio remoto vinculado.
* git push -u origin main: Envía los commits locales al repositorio remoto por primera vez.
* git pull origin main: Descarga los cambios hechos en GitHub hacia la PC.
* git push: Envía los nuevos commits del repositorio local a GitHub.

## Explicación de la sincronización
* **Sincronización Local -> GitHub:** Se preparan los archivos con git add ., se confirma la versión con git commit y se actualiza la nube mediante git push.
* **Sincronización GitHub -> Local:** Tras hacer un commit directo en GitHub, se descargan los cambios a la PC con git pull origin main.

## Descripción de los archivos del repositorio
* README.md: Contiene la documentación general y explicativa del proyecto.
* datos.txt: Archivo de texto plano utilizado para validar las modificaciones.

## Conclusión personal
Aprendí a manejar el flujo de trabajo de Git, comprendiendo el rol del Staging Area, el historial de commits y la importancia de mantener sincronizado el entorno local con un repositorio remoto.
