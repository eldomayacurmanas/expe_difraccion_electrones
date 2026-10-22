# expe_difraccion_electrones
## Como usar:

### Links para descargar
tex live:https://www.tug.org/texlive/windows.html
git:https://git-scm.com/install/windows

### Comandos para usar tex live
Comandos tex live:pdflatex archivo.tex

### Comandos para usar git 
comandos git:git clone linkdelrepositorio.git (se va a crear una carpeta con el repositorio creado en github. Necesito agregar tu cuenta para que tengas acceso. pasame el usuario)
```
git pull
# trabajar
git add .
git commit -m "Cambios claros"
git push
```

### CONFLICTOS: cuando no te deja hacer push es porque la otra persona lo actualizó antes de que vos subas. TENES QUE HACER un pull  
#### Caso A: No tocaron lo mismo: Se mezclan automáticamente los cambios.
Todo bien, volvé a hacer el push y va a funcionar.
#### Caso B: Editaron la misma parte: Aparece un conflicto  Git marcará algo así en el archivo:
```
<<<<<<< HEAD
Texto de tu compañero
=======
Tu texto
>>>>>>> main
```
Ahí deben:Elegir qué texto queda. Borrar las marcas. Guardar. Después: git add .
git commit -m "Resuelto conflicto"
git push
