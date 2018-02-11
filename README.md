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

## Varios repositorios remotos
Podemos configurar un mismo proyecto para sincronizar cambios con varios repositorios