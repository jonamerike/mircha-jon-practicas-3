# Practicas

## Creación de carpeta local

```bash
mkdir carpeta
cd carpeta
touch README.md
touch .gitignore
code .
```

## Inicialización de repositorio

```bash
git init
git config --local user.email tu@correo.com
git add .
git commit -m "Mensaje del cambio"
git branch -M main
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```

## Flujo básico de un cambio

```bash
git add .
git commit -m "Mensaje del cambio"
git push
```
