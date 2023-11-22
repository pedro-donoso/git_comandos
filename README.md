# Comandos útiles de Git

![Comandos GIT](https://th.bing.com/th/id/R.135f0e7cad3b6837f092205712792738?rik=mw7r1CD1r3LivQ&pid=ImgRaw&r=0)

#### 1. Inicializar control de versiones GIT (en el directorio dende se encuentra el proyecto):

```git init```

#### 2. Agregar todos los archivos:
    
```git add .```


#### 3. Borrar add:
    git reset

#### 4. Agregar commit:
    git commit -m "Primer commit"

#### 5. Borrar commit:
    git checkout --

#### 6. Ver listado de commits:
    git log

#### 7. Renombrar último commit:
    git commit --amend

#### 8. Crea una rama nueva:
    git checkout -b rama_nueva

#### 9. Ver rama actual:
    git branch

#### 10. Ir a la rama principal:
    git checkout master
    
#### 11. Traer rama:
    git merge rama_nueva

#### 12. Eliminar una rama:
    git branch -d rama_nueva

#### 13. Subir a repositorio remoto:
    git push

#### 14. Mezcla de add con commit:
    git commit -am "agregado"
