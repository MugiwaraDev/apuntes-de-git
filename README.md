# Curso Git desde 0
Sistema de control de versiones para el mantenimiendo eficiente
y confiable de archivos.

## Zonas de Git
1. Working Directory
2. Staging Area
3. .git Directory

## Flujo de Trabajo con Git
1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos, añadiendolos a tu área de preparación.
3. Confirmas los cambios, lo que toma los archivos tal y como están 
   en el área de preparación y alamcena esa copia instantánea de manera
   permanenete en tu directorio de Git.

## Configurando Git por primera vez
```
git config --global user.name "User Name"
git config --global user.email "email@email.com"
git config --global core.editor nano
git config --list
```

## Configuración SSH
1. Ejecutamos el comando `ssh-keygen -t rsa -C "correo@ejemplo.com"`.
El correo debe ser el mismo con el que nos registramos en GitHub para evitar posibles problemas.
Dejamos el passphrase vacío y damos enter.
Cuando nos pida la ruta escribimos lara ruta donde se generó la llave.

2. Iniciamos ssh-agent en background ejecutando el comando `eval "$(ssh-agent -s)"`.

3. Agregamos la llave ssh generada a ssh-agent ejecutando el comando `ssh-add` y la ruta de la llave.

4. Desde ahora podemos hacer pull y push sin que GitHub nos esté pidiendo los datos de acceso.