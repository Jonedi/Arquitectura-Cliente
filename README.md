# Cliente/Servidor
El siguiente proyecto se desarrollo para cumplir con la actividad 3 de la Unidad 1 de la materia Arquitectura de Software.

El proyecto trata de un formulario con las siguientes indicaciones:

- caja de texto: Agregar una tarea
- Aplicación: elegir "JavaScript", "NodeJS" o elegir una de las dos
- Prioridad: Elegir una prioridad "urgente" o "Relax"
- Hacer clic en procesar para enviar los datos.

los datos se guardarán en el localStorage del navegador, así que toda la vista, creación, edición y eliminación de datos se hará dentro del navegador.

## Ejecución Aplicación
Los siguientes pasos describen como ejecutar la aplicación.
### Instalación de paquetes
Primero hay que instalar los paquetes con los que el servidor ejecutará las rutinas. Para realizar esto, en una ventana de comandos ("Command", "MS-DOS", "Console" "GitBash", etc), dirigirse a la carpeta donde se encuentra el proyecto y digitar el siguiente comando:
```
npm install
```

### Compilar e iniciar servidor para desarollo
Una vez terminada la instalación de paquetes, el siguiente paso es iniciar el servidor escribiendo el comando en la ventana de comandos:
```
npm run serve
```
Esto creará un socket para acceder desde el navegador. Al finalizar dará la ruta de acceso al servidor, se puede copiar y pegar en un navegador o (ctrl + click izquierdo) con el teclado y ratón. Esto iniciará una ventana en el navegador y mostrará el proyecto

### Compilar y minificar para producción
Si se desea subir este proyecto en un servidor web y ejecutarlo en producción, se ejecuta el siguiente comando en la ventana de comandos:
```
npm run build
```

### Desarrollado por Jon Tmarz
Ver [más proyectos](https://jontmarz.appetz.com/).
