Paso 1: creamos el proyecto node con npm init y la carpeta Readme.md
Paso 2: Crear un repositorio local con git init
Paso 3: Crear un nuevo repositorio en github
Paso 4: Enlazar el repositorio local con el repositorio remoto de github. para ello usamos los comandos:
    -hacer un git add
    -hacer un git commit
    -git remote add origin https://github.com/e-nihilus/ejer2.git
    -git branch -M main
    -git push -u origin main
Paso 5: Añadimos Readme.md al stage con el comando git add Readme.md
Paso 6: Comprobamos el estado con git status
Paso 7: sacar el acchivo Readme.md del stage usando git reset --soft Readme.md