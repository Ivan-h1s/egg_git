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

# atajo --> $ git checkout -b rama-nueva-1
git add .  

git commit -m "creamos una rama nueva y agregamos otra guia"  

# ponemos el nombre de la rama nueva (la que estamos trabajando)
git push -u origin rama-nueva-1  

# merge nos situamos en la rama main, en este caso se llama igual 
git checkout rama-nueva-2 

# mergeamos con la rama que elejimos
git merge rama-nueva-1 -m "mensaje mergeador"  

# revertir merge
git reset --hard  

