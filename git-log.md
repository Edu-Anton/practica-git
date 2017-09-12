### git log
Muestra el historial de commits

`git log --pretty=format:"%h -%an, %ar : %s"`
Muestra el historial con el formato que le indicamos.

### Limitar la salida del historial
`git log -n`: Cambiamos la n por cualquier número entero, por ejemplo: `git log -2` nos mostrará los dos commits más recientes.

`git log --after="2016-04-08 00:00:00"` : Muestra los commits realizados después de la fecha especificada.

`git log --before="2016-04-08 00:00:00"` : Muestra los commits realizados antes de la fecha especificada.

Las banderas del comando `git log` se pueden usar según nos convenga, por ejemplo:
`git log --after="2016-04-07 12:00:00" --before="2016-04-07 12:30:00"`
