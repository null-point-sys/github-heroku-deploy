Node js app para clonar en local, deploy a repo github y de alli deploy automatico a Heroku sin CLI Heroku local.

Si se crea una app en Heroku y se conecta Github desde allí se puede hacer deploy automático y cada vez que cambie el código en Github se hace un build en Heroku.

Proceso para hacer push de una app a un repo github vacio:

$ cd carpeta/con-archivos-a-subir

$ git init

$ git add .

$ git commit -m “first commit”

$ git remote add origin https://github.com/rramname/MyCoolNodeApp.git

$ git push --set-upstream origin master
