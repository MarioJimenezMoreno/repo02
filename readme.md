# Comandos GIT

## Setup del repositorio

cd Desktop\ (Nos movemos al escritorio para trabajar mejor)  
mkdir *Repositorio* (Creamos un repositorio)    
cd *Repositorio* (Nos movemos al repositorio)


## Trabajando con la Staging Area
git status (Checkear Work Dir y Stag Area)  
git add . / git add <documento> (Añadir <documento> a Stag Area)  
git rm --cached <documento> (Devolver el <documento> a Work Dir)  
git commit -m "*texto*" (Comitear lo añadido con un mensaje)  
git commit -am "*texto*" (Comitear y añadir)  
git log (Log de commits)  
git log --all --decorate --oneline --graph (Log formato "A DOG")  
git checkout *número de commit* (Moverse a un commit específico)  
git checkout master (Volver a master)  
git checkout master~*número* (Bajar *número* commits desde master)  

## Trabajando con el Repositorio Remoto
git remote -v (Ver servidor)  
git push (Pushear a github)  
git pull (Pullear de github)  
git clone *link* (Clonar repositorio con un link)  
git remote remove origin (Eliminar vinculo entre repo y github)
