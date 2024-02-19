<h1>Ramas_Básicas</h1>

* Creamos el repositorio e inicializamos el repositorio local \
<code><b>git init</b></code> \
<code><b>git branch -M main</b></code> \
<code><b>git remote add [repositorioRemoto]</b></code>


* Hacemos los cambios en la rama main \
<code><b>git add [cambios]</b></code> \
<code><b>git commit -m [mensaje]</b></code> \
<code><b>git push origin main</b></code>


* Creamos y cambiamos a la rama nueva_rama \
<code><b>git checkout -b nueva_rama</b></code>


* Hacemos los cambios en la rama nueva_rama \
<code><b>git add [cambios]</b></code> \
<code><b>git commit -m [mensaje]</b></code> \
<code><b>git push origin nueva_rama</b></code>


* Hacemos checkout a main y hacemos merge de la nueva_rama a main, resolviendo los conflictos que pudiese haber \
<code><b>git checkout main</b></code> \
<code><b>git merge main nueva_rama</b></code> \
<code><b>git push origin main</b></code>