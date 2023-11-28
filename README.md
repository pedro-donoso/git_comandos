# Comandos útiles de Git

![Comandos GIT](https://th.bing.com/th/id/R.135f0e7cad3b6837f092205712792738?rik=mw7r1CD1r3LivQ&pid=ImgRaw&r=0)

#### 1. Crear carpeta en el escritorio con la terminal:

```
mkdir git_curso
```
#### 2. Ingresar a la carpeta creada desde terminal:

```
cd git_curso
```

#### 3. Inicializar control de versiones GIT desde terminal vscode y enlazar con repositorio en github:

```
git init
```
#### 4. Crear archivo index.html y agregar:

```
git add .
```
#### 5. Ver estado del Proyecto:

```
git status
```

#### 6. Commitear cambios:

```
git commit -m "primer commit"
```

#### 7. Pushear cambios para publicar rama:

```
git push
```

#### 6. Crear nueva rama develop:

```
git branch develop
```

#### 7. Cambiar a nueva rama creada:

```
git switch develop
```


#### 8. Añadir un fichero o versionar todos los cambios:
    
```
git add nombrearchivo.extension
```

```
git add .
```

#### 9. EDITAR ARCHIVO: Realizar cambios en el fichero (sin commitear)

#### 10. Volver al estado anterior del fichero antes de editarlo:

```
git checkout nombrearchivo.extension
```

ESCRIBIR HASH (IDENTIFICADOR ÚNICO) DEL COMMIT
```
git checkout 3e69287
```

#### 11. Traer cambios a develop:

```
git switch develop
```

#### CREAR UN EL FICHERO nombrearchivo.extension

#### 12. Revisar todos los commits:

```
git log
```

#### 13. Revisar todos los commits gráficamente:

```
git log graph
```
#### 14. Revisar cada commit en una línea:

```
git log --oneline
```

#### 15. Decorar commits:

```
git log --graph --decorate --all --oneline
```

#### 16. Crear alias, entre comillas agregar decoración

```
git config --global alias.nombrealias "log --graph --decorate --all --oneline"
```

#### 17. Utilizar alias

```
git nombrealias
```

#### 18. Ignorar fichero

#### CREAR ARCHIVO .gitignore EN LA RAÍZ DEL PROYECTO

#### AGREGAR FICHEROS DENTRO DE ESTE ARCHIVO

```
**/.nombrearchivo.extension
```

#### EDITAR FICHEROS

#### 19. Revisar diferencias entre ficheros commiteados y sin commitear.

```
git diff
```
#### 20. Moverse entre commits:

COPIAR FINAL DEL HASH (CÓDIGO ÚNICO) DEL COMMIT DONDE QUEREMOS SITUARNOS

```
git checkout 3e69287
```

#### 21. Revisar dónde apunta la cabecera (HEAD):

```
git log
```

#### 22. Resetar commits(UTILIZAR HASH DEL COMMIT):

#### RESET FUNCIONA PARA COMMITS ANTES O DESPÚES DE LA CABECERA (HEAD)
```
git reset 3e69287
```

#### 23. Recuperar commits borrados

#### MUESTRA HISTORIAL COMPLETO DE COMMITS

```
git reflog
```

#### GIT RESET (HASH) PARA POSICIONAR CABECERA (HEAD)

#### 24. Etiquetar commit:

agregar nombre al commit puntual

```
git tag nombretag
```

#### 25. Mover cabecera (HEAD) entre Tags:

```
git switch tags/nombretag
```

#### 26. Mover cabecera (HEAD) a la ubicación del main:

```
git switch main
```

#### 27. Crear nueva funcionalidad (feature):

```
git branch nombrefeature
```

#### 28. Moverse a nueva rama creada:

```
git switch nombrefeature
```
#### REALIZAR CAMBIOS Y COMMITEAR

#### 29. Ver todas las ramas:
```
git branch
```

#### 30. Realizar Merge:

```
git merge main
```

#### 31. Revisar commits mergeados

UTILIZAR ALIAS CREADO

```
git tree
```
#### 32. Guardar temporalmente (local)

```
git stash
```
#### 33. Revisar lista de pendientes:

```
git stash list
```

#### 34. Traer cambios guardados temporalmente:

```
git stash pop
```
#### 35. Eliminar stash guardado:

```
git stash drop
```

















