
# comandos utiles git

1. git init             {inicia y crea el repositorio de git}
2. git add .            {agrega y prepara todos los archivos para "fotografia"}
3. git reset .          {para revertir el git add .}
4. git commit -m ""     {toma la "fotografia" de los archivos agregados al repositorio}
5. git checkout -- .    {recupera los archivos y modificaciones del ultimo commit}
6. git log              {vista de los commit realizados}
7. git commit --amend   {arreglar el ultimo commit}
# i para escribir, para salir -> Esc, luego :wq!
8. git checkout -b rama-nombre  {para trabajar en una rama y no en el repositorio main}
9. git branch                   {muestra las ramas}
10. git checkout master         {para cambiar a la rama master}
11. git merge rama-nombre       {se trae lo de rama-nombre y lo une a la rama actual (por lo general master)}
# i para escribir, para salir -> Esc, luego :wq!
12. git branch -d rama-nombre   {para eliminar una rama}
# remoto
13. git remote add origin https://github.com/kevinlflorez/comandosgit.git
14. git branch -M main
15. git push -u origin main
# usar los comandos para llevarlos al repositorio remoto
16. git push            {despues de hacer nuevo commit, usar este comando para subir al repositorio remoto}
17. git commit -am ""   {cuando ya se esta haciendo seguimiento a un directorio, se omite el add .}
# bonus no nombrado
18. git pull            {para traer todos los ultimos cambios antes de actualizar los repositorios}

