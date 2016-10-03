1- Utilizo **git reset --hard HEAD~1** porque así quito todo lo que e hecho y no quede rastro en
el working copy

2- Uso **git reflog** para localizar el *SHA* del commit anterior y con este uso un **git reset
--hard** con el *SHA* para volver a dejarlo todo como estaba

3- El merge del paso 13 no causa problema ya que es un **merge fast forward**

4- Sí, el merge del paso 19 causo un problema, ya que la rama htmlify tenia un *commit*
más que la rama styled

5- El merge del paso 21 fue un **merge fast forward** ya que styled estaba más avanzada
que master y no causa problema

6- En el paso 25 utilice el comando **git graph** que se compone de
**git log --graph --decorate --pretty=oneline**

7- En el paso 26 podría haber sido un **merge fast forward** ya que la rama title tenía un *commit* más que la rama master

8- En el paso 27 use **git reset HEAD~1** para no perder los cambios del *working copy*

9- En el paso 28 use **git reflog** y **git checkout** para moverme a como estaba cuando me cambie de rama y uso **git checkout --** para descartar los cambios 

10- En el paso 29 use **git branch -D** 

11- En el paso 30 uso **git reflog** para encontrar el *SHA* y después **git reset --hard** para cambiarme (después de dar varias vueltas)

12- En el paso 32 uso **git log** para encontrar cual es el primer *commit* y despúes uso **git checkout** para cambiarme a este

13- En el paso 33 uso **git log** para encontrar cual es el ultimo commit y despúes uso **git checkout** para cambiarme a este y otra vez **git checkout** para cambiar a la rama master ya que estoy en *detached head*

