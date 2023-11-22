# Comandos útiles de Git

![Comandos GIT](https://th.bing.com/th/id/R.135f0e7cad3b6837f092205712792738?rik=mw7r1CD1r3LivQ&pid=ImgRaw&r=0)

#### 1. Inicializar control de versiones GIT (en el directorio dende se encuentra el proyecto):

```
git init
```

#### 2. Establecer nombre de rama inicial y cambiar Nombre a rama principal del proyecto:

```
git config --global init.defaultBranch main
```

```
git branch -m main
```

#### 3. Ver estado del Proyecto:

```
git status
```

#### 4. Añadir fichero o versionar todos los cambios:
    
```
git add nombrearchivo.extension
```

```
git add .
```

#### 5. Agregar commit con mensaje:
```
git commit -m "Primer commit"
```

#### 6. Revisar commit creado:

```
git log
```

#### EDITAR ARCHIVO

#### 7. Volver al estado anterior del fichero antes de editarlo :

```
git checkout nombrearchivo.extension
```

#### 8. Volver  al fichero anterior commiteado:

```
git reset
```

#### INGRESAR EL FICHERO nombrearchivo.extension

#### 9. Revisar todos los commits:

```
git log
```

#### 10. Revisar todos los commits gráficamente:

```
git log graph
```
#### 11. Revisar cada commit en una línea:

```
git log --oneline
```

#### 12. Decorar commits:

```
git log --graph --decorate --all --oneline
```

#### 13. Crear alias, entre comillas agregar decoración

```
git config --global alias.nombrealias "log --graph --decorate --all --oneline"
```




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
