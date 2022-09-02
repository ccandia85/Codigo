# Primer dia con Git/github

Comando para configurar el usuario y el correo electronico

*Sirve para poder ver la versión de git

```bash
git --version
```

* Para configurar el correo
```bash
git config --global user.email "email"
```

* Para configurar el username

```bash
git config --global user.name "nickname"
```

* Sirve para iniciar el control de versiones (git). Solo se utiliza una vez por carpeta.

```bash
git init
```
* Para ver el estado de nuestros cambios
```bash
git status
```
* Para agregar los archivos a la memoria de la PC.
```bash
git add .
```

```bash
git add READ.md
```
* Crea el registro de los cambios realizados.

```bash
git commit -m "Creando mi primer commit"
```

* Poder ver el historial de Commit.
[x] Git log retorna un "id" con este 
ID vamos a poder ver el detalle o
ambios que se hicieron en se commit.

```bash
git log
```
* Muestra el commit consultado
```bash
git show ID_commit
```

* Cambiar el nombre de la rama a Main
```bash
git branch -M main
```

* Descripcion
```bash
git remote -v
```

* Descripción
```bash
git push origin main
```
* Seguidamente sign in browser, 
login con tu cuenta de github,
luego autorizar (boton verde).
seguidamente, actualizar la pagina
en tu github de tu repositorio.
Debería mostrar lo desarrollado en README.md
