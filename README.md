
# Pasos para inicializar un repositorio

1. Inicializar el repositorio localmente

`git init`

2. Indicarle que archivos preparar para el siguiente punto de guardado

`git add .` 

`git add nombreDeArchivo.extension`

3. Generar la versión o punto de guardado con los archivos que previamente se prepararon

`git commit -m "Mensaje descriptivo"`

4. Crear la rama principal "main" en nuestro repositorio

`git branch -M main`

5. Ir a tu cuenta de Github y crear un nuevo repositorio en la nube

6. Enlazar el repositorio en la nube con nuestro repositorio local

`git remote add origin url-al-repositorio-nuevo`

7. Publicar los cambios del último commit hacia nuestro repositorio en la nube

`git push -u origin main`

## Para actualizar el repositorio
Seguir los pasos 2, 3 y 7
