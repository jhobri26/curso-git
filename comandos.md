"comandos git

#ver la versión 
git --version

#configuracion
git config --global user.name "jhobri26" 
git config --global user.email jhobri26@gmail.com


#inicializacion en git
git init

#muestra cambios
git status


#agrega archivo
git add file1
git add -a

#ver historial
git log


#agregar al repositorio local
git commit comandos.readme -m "primer commit"

#envia al repositorio
git push

#diferenciador de cambios
test git diff

----uyno

git branch -r
 git branch feature1 |"crear rama"

 #cambiar de rama
 git switch

#sincronizar
git fetch

#saber que ramas fueron fusionadas | no fusionadas
git branch --merge
git branch --no merge

#ver historia
git log --oneline
git log --graph

#fech sincorinizar

#probando webhooks