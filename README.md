# Laboratorio-2
Academico

## Autor
Kendal Martínez


## Configuración inicial

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "correo@ejemplo.com"
```



## Creación del proyecto

```bash
mkdir Laboratorio2
cd Laboratorio2
touch index.html styles.css
```



## Inicialización de Git

```bash
git init
git branch -M main
```


## Primer commit

```bash
git add .
git commit -m "Estructura inicial del proyecto"
```



## Ver historial

```bash
git log --oneline
```


##  Crear rama desarrollo

```bash
git checkout -b desarrollo
```


##  Cambios en index

```bash
git add .
git commit -m "Agrega contenido en index"
```



## Merge de ramas

```bash
git checkout main
git merge desarrollo
```


## Ver diferencias

```bash
git diff
```


## Commit temporal

```bash
git add .
git commit -m "Cambio temporal"
```


## Eliminar último commit

```bash
git reset --hard HEAD~1
```


## Recuperar commit

```bash
git reflog
git reset --hard ID_DEL_COMMIT
```


##  Crear .gitignore

```bash
touch .gitignore
```

Contenido:

```
*.log
.env
.vscode/
```

---

## Commit gitignore

```bash
git add .
git commit -m "Agrega gitignore"
```


## Conectar con GitHub

```bash
git remote add origin https://github.com/KendalMartinez/Laboratorio-2.git
git pull origin main --allow-unrelated-histories
git push -u origin main
```


## Crear rama login

```bash
git checkout -b login
touch login.html
```


## Commit login

```bash
git add .
git commit -m "Agrega login"
```


## Subir rama login

```bash
git push origin login
```


##  Pull Request

1. Ir a GitHub
2. Crear Pull Request desde la rama `login` hacia `main`
3. Revisar cambios
4. Hacer merge

