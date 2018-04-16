### git log
Muestra el historial de commits

`git log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indicamos.

 ### limitar la salida del historial
 `git log -n`: Cambiamos la n por cualquier número entero, por ejemplo: `git log -2` nos mostrará los 2 commits más recientes.

 `git log --after="2018-04-15 00:00:00"`: Muestra los commits realizados después de la fecha especificada.

`git log --before="2016-04-07"`: Muestra lso commits realizados antes de la fecha especifica.

las banderas del comando `git log` se pueden uutilizar los coomits realizados antes de la fecha especificada.

`git log --after="2018-04-15 00:00:00" --before="2018-04-15 23:30:00"`
