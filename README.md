[Versión 0.7.2]: #
# aux_plus - Colección de scripts auxiliares para el desarrollo en bash

En esta colección de scripts hay algunos programas y wrappers simples que permiten realizar tareas que se necesitan ocasionalmente en el desarrollo de script de bash. Algunas son un comando que no hace nada como "./nada" un comando que me muestre el MOTD para comprobar que se ve correctamente como "./yo", comprobar que muestre el return correctamente como "./error" o mostrar todas las combinaciones de colores de la terminal para elegir el mas adecuado como "./colores".

---
## Estado del proyecto
- Los scripts existentes funcionan y actualmente estan siendo usados.
- Muchos scripts se pueden mejorar en detalles menores.
- A medida que se necesiten nuevos se iran añadiendo y mejorando.

### Ficheros
- Scripts*: colores, error, fecha, nada, sis, yo
- LICENSE: contenido de la licencia
- README.md: información del proyecto
- .gitignore: define elementos a ignorar

---
## Instalación
No requiere instalación

### Lenguaje
- Bash

### Dependencias
No existen dependencias

### Sistemas operativos compatibles
Probado en:
- Debian

---
## Recomendación
Para un uso mas ágil se puede crear una carpeta para script de forma que todos los que se añadan se puedan llamar desde la propia terminal como cualquier otro comando.

Esto se puede conseguir añadiendo a ~/.bashrc la línea:

```bash
    export PATH=$PATH:/ruta/a/carpeta/con/scripts
```

---
## Uso
Solo se han de descargar los scripts deseados, darles los permisos correctos y ejecutarlos directamente en la terminal. Cada herramienta está en un solo archivo. A continuación se explica brevemente el uso de cada una.

### colores
```bash

    ./colores
```
- Muestra todos los colores y una pequña ayuda para su uso
- Con una 'c' como argumento muestra todas las combinaciones posibles.
### error
```bash

    ./error 4
```
- Devuelve como valor de error el argumento pasado
- Útil para comprobar si las salidas darán correctamente
### fecha
```bash

    ./fecha
```
- Muestra la fecha en un formato numérico agradable
- Mirar sus opciones para añadir color y cambiar formato
### nada
```bash

    ./nada
```
- No hace nada
- Útil para añadir en algúna condición o bucle mientras se desarrolla
### sis
```bash

    ./sis
```
- Muestra información variada del sistema
- Sistema operativo, kernel, CPU, hilos, RAM, Discos...
### yo
```bash

    ./yo
```
- Muestra el MOTD configurado actualmente en el sistema
- Útil para comprobar que se muestra correctamente

---
## Licencia
Este proyecto está licenciado bajo GPLv2 - consulta el archivo LICENSE para más detalles.

---
## Autor
>**Alex**
- Github: [https://github.com/4lexKy](https://github.com/4lexKy)
- Email: [alex.correu@pm.me](mailto:alex.correu@pm.me)

---
