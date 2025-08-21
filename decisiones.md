### Gestión del repo
1. fork desde el repositorio base con el nombre de tp1_inge3 --> genero una copia en mi git
2. `git clone https://github.com/Agus-03/tp1_inge3.git` --> descargo copia local

### Configuración de identidad de Git
1.  `git config user.name "Agus"` --> commits a mi nombre
2.  `git config user.email "2201746@ucc.edu.ar"` --> commits con mi correo

### Archivo decisiones.md
1. `type nul > decisiones.md`
2. `start decisiones.md`
3. esta descripción

### Nueva funcionalidad
1. `git branch NewFunction` --> creo la rama para crear nuevas funciones que luego serán agregadas al main si salen bien
2. `git checkout NewFunction` --> me voy a esa rama
3. desarrollo la funcion `ovejas` que imprime "beee" en consola
4. `git status` para verificar el estado de los archivos en la rama
5. `git add src/app.js` para añadir los cambios realizados en el archivo
6. `git commit -m ""` para añadir el mensajito de que creamos la funcion `ovejas`
7. `git checkout main` para volver a la main
8. `git merge NewFunction` para traer los cambios que realizamos en la rama mencionada, a la rama actual
9. `git push origin main` para pushear los cambios al repo de git (fast-forward merge porque a la main no la modificamos
10. [acá me olvidé que los commits eran 2, asiq eliminé y volví a crear la rama de NewFunction para poder seguir]
11. repetimos del 2 al 9, con el cambio que ahora invocamos la funcion `ovejas` en app.js (porque me había olvidado, y bueno queda el commit)
    Ambos commit son atómicos y claros, y usé una rama llamada NewFunction.
    Esta rama se llama así y se fusiona tan rápido porque elegí una estrategia TBD, trabajando en ramas de corta duración que se fusionan rápidamente en la rama principal varias veces al día.
