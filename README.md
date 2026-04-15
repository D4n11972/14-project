Tu directorio local no tiene remoto configurado aún, y https://github.com/D4n11972 es solo tu perfil, no la URL de un repositorio.

Paso 1: crea el repositorio en GitHub
Entra a https://github.com/D4n11972 y crea un repositorio nuevo, por ejemplo:

nombre: 14-project
privado o público según prefieras

Paso 2: configura el remoto en tu repositorio local
cd /Users/g5/Desktop/14-project
git remote add origin https://github.com/D4n11972/14-project.git

Paso 3: sube los cambios
git add nuevo_archivo.html
git commit -m "Agrega nuevo_archivo.html"
git push -u origin main
