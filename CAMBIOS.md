### Installation

_Lista de todos los comandos de:._

* Crear un nuevo repositorio en la línea de comando
* Subir un repositorio local existente desde la línea de comando 
* Otros comandos


<br />
<div align="center">
  <h3 align="center">Enlaces de interes</h3>
    <br />
    <a href="https://github.com/alavaro-dev/REGLAS-README/edit/main/COMMIT.md">Convenciones de como hacer un Commit</a></li>
    ·
    <a href="https://github.com/alavaro-dev/REGLAS-README/edit/main/README.md">Plantilla README</a>
  </p>
</div>



## Crear un nuevo repositorio en la línea de comando

* Copia estos comandos cambiando: "# nombre_repositorio", "first commit", https://github.com/username/repo.git
```sh
    echo "# nombre_repositorio" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/username/repo.git
    git push -u origin main
```



* Subir un repositorio local existente desde la línea de comando cambiando: https://github.com/username/repo.git 
```sh
    git remote add origin https://github.com/username/repo.git
    git branch -M main
    git push -u origin main
```


* Otros comandos

Configurar Nombre que salen en los commits
```sh
    git config --global user.name "username"
```

Configurar Email
```sh
    git config --global user.email user@gmail.com
```

Iniciamos GIT en la carpeta donde esta el proyecto
```sh
    git init
```

Clonamos el repositorio de github o bitbucket
```sh
	git clone https://github.com/username/repo.git
```

Añadimos todos los archivos para el commit
```sh
	git add .
```

Añadir seleccionando los archivos
```sh
    git add -i
```

Hacemos el commit
```sh
 git commit -m "Texto que identifique por que se hizo el commit"
```
<a href="https://github.com/alavaro-dev/REGLAS-README/edit/main/COMMIT.md">Convenciones de como hacer un Commit</a></li>

subimos al repositorio
```sh
	git push origin main
```

