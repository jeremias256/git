
## Help:
git help :



### git commit -help :



## Inicio:
git --help config
git config --global user.name "jeremias256"
git config --global user.email "jere.menacho@gmail.com"
git config --global -e :    Listar comandos  (a modifica / :wq! guardar y salir)
git init --global init.defaultBranch <name>


 
## teclas:
q : quit
a modifica / :wq! guardar y salir)


## status
git status --short          Información resumida



## comunes 
git log                     Información de los commits
git log --online            Información de los commits resumido
git log --online --decorate -all --graph
git status                  Información del estado
git add <name>              Agrega un archivo en especifico
git add .                   Agrega todo el directorio
git add *.html              Agrega todo lo que finaliza .html
git commit -m "mensaje"     
git commit -am "mensaje"    Agrega y commitea si ya sigue los archivos
git reset <name>            Quita un archivo del add
git checkout -- .           Restaura al ultimo commit


## ramas:
git branch:                                    Mostrar en que rama estoy    trabajando.
git config --global init.defaultBranch main:   Setear el name de la rama
git branch -m master main:                     Cambia el nombre de la rama



## archivos
.gitkeep            Para agregar seguimiento a carpetas vacías



## alias
git config --global alias.s "status --short"
git config --global -e



## utils
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

=> git lg

14-15-16-17
