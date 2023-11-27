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
git checkout develop
```


#### 6. Añadir fichero o versionar todos los cambios:
    
```
git add nombrearchivo.extension
```

```
git add .
```

#### 7. EDITAR ARCHIVO: Realizar cambios en el fichero (sin commitear)

#### 8. Volver al estado anterior del fichero antes de editarlo:

```
git checkout nombrearchivo.extension
```

ESCRIBIR HASH (IDENTIFICADOR ÚNICO) DEL COMMIT
```
git checkout 3e69287
```


#### 11. Traer cambios a develop:

```
git checkout develop
```

#### INGRESAR EL FICHERO nombrearchivo.extension

#### 12. Revisar todos los commits:

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

#### 14. Utilizar alias

```
git nombrealias
```

#### 15. Ignorar fichero

CREAR ARCHIVO .gitignore EN LA RAÍZ DEL PROYECTO

AGREGAR FICHEROS DENTRO DE ESTE ARCHIVO

```
**/.nombrearchivo.extension
```

EDITAR FICHEROS

#### 16. Revisar diferencias entre ficheros commiteados y sin commitear.

```
git diff
```
#### 17. Moverse entre commits:

COPIAR FINAL DEL HASH (CÓDIGO ÚNICO) DEL COMMIT DONDE QUEREMOS SITUARNOS

```
git checkout hash
```

#### 18. Revisar dónde apunta la cabecera (HEAD):

```
git log
```

#### 19. Resetar commits:

RESET FUNCIONA PARA COMMITS ANTES O DESPÚES DE LA CABECERA (HEAD)
```
git reset 3e69287
```

#### 20. Recuperar commits borrados

MUESTRA HISTORIAL COMPLETO DE COMMITS

```
git reflog
```

GIT RESET (HASH) PARA POSICIONAR CABECERA (HEAD)

#### 21. Etiquetar commit:

agregar nombre al commit puntual

```
git tag nombretag
```

#### 22. Mover cabecera (HEAD) entre Tags:

```
git checkout tags/nombretag
```

#### 23. Mover cabecera (HEAD) a la ubicación del main:

```
git checkout main
```

#### 24. Crear nueva funcionalidad (feature):

```
git branch nombrefeature
```

#### 25. Moverse a nueva rama creada:

```
git switch nombrefeature
```
REALIZAR CAMBIOS Y COMMITEAR

#### 26. Ver todas las ramas:
```
git branch
```

#### 26. Realizar Merge:

```
git merge main
```

#### 27. Revisar commits mergeados

UTILIZAR ALIAS CREADO

```
git tree
```


















