# practica guia 15
git init
git add .
git commit -m "guia 5"
git branch -M main
git remote add origin https://github.com/Ivan-h1s/git_egg_.git
git push -u origin main

# creamos nueva rama
git branch rama-nueva-1

# nos movemos a la rama nueva
git checkout rama-nueva-1

git add . 
git commit -m "creamos una rama nueva y agregamos otra guia"

# ponemos el nombre de la rama nueva (la que estamos trabajando)
git push -u origin rama-nueva-1