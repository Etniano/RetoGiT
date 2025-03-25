# RepoNoEvaluable
COMO USAR GITHUB
1. Crear cuenta en github
2. Abrir proyecto en Visual Studio Code
3. Entrar en Gihub.com y crear un repositorio
4. Conectar  el repositorio a archivos locales de tal manera:
- En la terminal de VSC escribir git init
- Copiar la sexta linea "git remote add origin https...." en el terminal. Al presionar enter no aparece nada.
- Haces un git status y te indica que hay archivos que no estan comitados.
- Usar git add . (puedes escribir el nombre del archivo que quieres commitar o añadir solo un .) para añadirlos todos. Apretamos ENTER.
- Comprobar con git status y aparece en verde los archivos que se quieren añadir
- Hacer git commit -m "mensaje" y al presionar ENTER indica que se ha creado un archivo.
- Si volvemos a hacer un git status aparece que no hay nada para commit.
- Introducimos git push y aparece un error y te indicará que paso debes seguir por que es la primera vez. Copias el git push --set y pegas en la nueva linea.
- Ya se ha subido a github.

RESUMEN:
(1. GIT STATUS, 1. GIT ADD., 3. GIT STATUS, 4. GIT COMMIT -M, 5. GIT PUSH)
 Nota para vago: Al hacer un GIT CLONE desde cmd en la carpeta será mas facil ya que github se enlaza automaticamente.