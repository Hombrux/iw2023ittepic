# iw2023ittepic
git innit 
git add README.md
git commit -m "Initial commit"
git push origin master 

touch privado.txt
mkdir privada
touch .gitignore

touch 1.txt
git tag v1.0
git add 1.txt
git add README.txt
git add .gitignore
git commit -m "Creacion del TAG |.gitignore| 1.txt"
git push main 

## Creacion de Tabla
|Nombre           |Github                          |
|       ---       |             ---                |
|Eduardo Meza     |https://github.com/EduardoMezaA | 
|Marlett Marín    |https://github.com/Alessandra222|
|Valeria Gutierrez|https://github.com/valgd        |
|Gustavo Aguilar  |https://github.com/gsuvo        |
|Daniel Lopez     |https://github.com/dloram15     |

## Colaboradores 
![1](https://github.com/Hombrux/iw2023ittepic/blob/main/assets/colaboradores.png)


# Practica (Segunda parte)
## Crear Rama
git checkout -b v0.2
## Añadir archivo
touch 2.txt
git push origin v0.2

## Merge Directo 
git checkout main
git merge v0.2

## Merge con conflicto
git checkout main
-Poner 'Hola' en 1.txt
git commit -m "Hola"
git checkout v0.2
-Poner 'Adios' en 1.txt
git commit -m "Adios"
git checkout main
git log 
Arreglar el conflicto 
git commit -m "Solucion de conflicto"

## Borrar rama 
git tag v0.2
git branch -d v0.2

## Listado de cambios 
git log 


