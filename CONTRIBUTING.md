# CONTRIBUTING
Clonar el repositorio usando el siguiente comando:
```console
git clone https://github.com/7intiaditi7/Landing-page.git
```

## Bajar los cambios más recientes de main:
```console
git pull
```

## Crear una branch nueva
```console
git checkout -b <nombre-branch>
```

## Bajar los cambios más recientes de main desde otra branch:
```console
git pull origin master
```

## Agregar los cambios a stage:
```console
git add .
```
o
```console
git add <ruta-del-archivo>
```
## Verificar el status de los archivos en stage
```console
git status
```

## Hacer commit a los cambios
```console
git commit -m "<mensaje-commit>"
```

## Subir los cambios
```console
git push
```

## Cambiar a main
```console
git checkout main
```

## Resolver conflictos
En Visual Studio Code, seleccionar **Source Control** en la barra de navegar izquierda y luego: 
- Seleccionar el archivo con conflictos
- Arreglar los conflictos
- Guardar y agregar el archivo en stage
- Ejecutar `git commit`
- Ejecutar `:q` cuando entre en el editor de texto
- Ejecutar `git push` 

## Commits
Los commits deberán seguir la siguiente estructura
```
<type>[optional scope]: <description>
```

## Types
1. **fix:** a commit of the type fix patches a bug in your codebase (this correlates with PATCH in Semantic Versioning).
2. **feat:** a commit of the type feat introduces a new feature to the codebase (this correlates with MINOR in Semantic Versioning).