# Comandos GIT

## Setup del repositorio

cd Desktop\ (Nos movemos al escritorio para trabajar) mejor  
mkdir <NuevaCarpeta> (Creamos un repositorio con el nombre que queramos)  
cd <NuevaCarpeta> (Nos movemos al repositorio)


## Trabajando con la Staging Area
git status (Checkear Work Dir y Stag Area)  
git add . / git add <documento> (Añadir <documento> a Stag Area)  
git rm --cached <documento> (Devolver el <documento> a Work Dir)  
git commit -m "texto”> (Comitear lo añadido)  
git log (Log de commits)  
git log --all --decorate --oneline --graph (A DOG)  
git checkout [commit] (Moverse a [commit])  
git checkout master (Volver a master)  
git checkout master~[n] (Bajar [n] commits desde master)  

## Trabajando con el Repositorio Remoto
git remote -v (Ver servidor)  
gut push (Pushear a github)  
git pull (Pullear de github)  
git clone [link] (Clonar [link] repositorio)  
git remote remove origin (Eliminar vinculo entre repo y github)
