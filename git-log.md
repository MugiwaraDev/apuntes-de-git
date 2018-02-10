### git log
Muetras el historial de commits

`-n`
Nos mostrará el número de commits indicados.

`--oneline`
Nos muestra el historial abreviado.

`--graph`
Añade un pequeño gráfico ASCII mostrando el historial de 
ramificaciones y uniones.

`git log --pretty=format:"%h - %an, %ar : %s"`
Mustra el historial con el formato que le indicamos.

`git log --decorate --oneline --all --graph`
Este comando nos muestra el historial en una sola línea por commit.