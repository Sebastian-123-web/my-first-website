# Git y Github

## Comprobar que Git este Instalado

```
git --version
git version 2.28.0.windows.1
```

## Configuracion Global

```
git config --global user.name "Sebastian-123-web"
git config --global user.mail "sebastian09_26@hotmail.com"
```

## Crear un repositorio desde GitHub

## Inicializamos Git

```
git init
```

## Enlazar nuestro repositorio remoto

```
git remote add origin https://github.com/Sebastian-123-web/my-first-website.git
```

## Definir la rama principal

```
git branck -M main
```

## Subir los cambios

```
git add --all
git commit -m "my first commit"
git push origin main
```