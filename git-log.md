### git log
Muestra el historial de commits

`git log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indicamos

### Limitar la salida del historial

`git log -n` : Cambiamos la n por cualquier numero entero por ejemplo: `git log -2` nos mostrara los 2 commits mas recientes.

`git log --after="2018-02-10 00:00:00"`:Muestra los commits realizados despues de la fecha especificada.

`git log --before="2018-02-10 00:00:00"`:Muestra los commits realizados antes de la fecha especificada.

Las banderas del comando `git log` se pueden usar juntas segun convenga, por ejemplo :
`git log --after="2018-02-10 12:00:00" --before="2018-02-10 12:30:00"`
 
`git log --oneline`
Este comando nos muestra el historial en una sola linea por commit.