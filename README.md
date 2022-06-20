
### Help:
git help :



### git commit -help :



### Inicio:
git --help config
git config --global user.name "jeremias256"
git config --global user.email "jere.menacho@gmail.com"
git config --global -e :    Listar comandos  (a modifica / :wq! guardar y salir)
git init --global init.defaultBranch <name>


 
### teclas:
q : quit



### comunes 
git status          Información del estado
git add <name>      Agrega un archivo en especifico
git add .           Agrega todo el directorio
git reset <name>    Quita un archivo del add
git checkout -- .   Restaura al ultimo commit


### ramas:
git branch:                                    Mostrar en que rama estoy    trabajando.
git config --global init.defaultBranch main:   Setear el name de la rama
git branch -m master main:                     Cambia el nombre de la rama