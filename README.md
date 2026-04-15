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

## Anexos
<img width="1123" height="719" alt="1" src="https://github.com/user-attachments/assets/e2bc26c8-9c1b-4b03-b210-fb7fbfb8bb77" />

<img width="1093" height="725" alt="2" src="https://github.com/user-attachments/assets/44624ad2-798e-4693-b0f0-257519238a7b" />

<img width="748" height="400" alt="3" src="https://github.com/user-attachments/assets/e0235696-acfb-40e8-b6f1-b956fa5960a1" />

<img width="821" height="412" alt="4" src="https://github.com/user-attachments/assets/38fc4852-a1ad-4d36-8b41-4f1a50eb17d9" />

<img width="801" height="400" alt="5" src="https://github.com/user-attachments/assets/4b1e8f3e-ed00-4b97-87aa-9f72f11d857a" />



