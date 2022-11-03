##Crear un nuevo repositorio desde la linea de comandos 

    echo "# GitTest001" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/usuario/Nombre_Repositorio.git
    git push -u origin main
  
##  Realizar un _push_ a un repositorio existente en GItHub

    git remote add origin https://github.com/usuario/Nombre_Repositorio.git
    git branch -M main
    git push -u origin main


