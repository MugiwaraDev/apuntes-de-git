### git tag

Este comando lista las etiquetas en orden alfabético; el orden en el que aparecen no tiene mayor importancia.

`git tag v1.1 dev`
Una etiqueta ligera no es más que un checksum de un commit guardado en un archivo, no inclye más información. Para crear una etiqueta ligera, no pasamos las opciones -a, -s ni -m.

`git tag -a v1.0 -m "mi versión 1.0"`
Se guardan en la base de datos de Git como objetos enteros. Tienen un checksum; contienen el nombre del etiquetador, correo electrónico y fecha; y tienen un mensaje asociado.