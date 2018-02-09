### Renombrar archivos
```
git mv file_from file_to
```

Equivalente a los siguiente pasos:
1. Renombrar el archivo manualmente
2. `git rm file_from` para eliminar el archivo con git.
3. `git add file_to` para agregar el archivo con el nuevo nombre.