
![Mardown Links](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

# Markdown Links

Es una librería que encuentra todos los links dentro de un archivo Markdown. Se encarga de analizar dichos archivos dentro del directorio, otorgando diferentes datos y estadisticas. Entre ellos, el estado de cada link, permitiendo verificar si se encuentran funcionales o no. Todos estos resultados son visibles desde la terminal.


## Guía de uso <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path d="M11 14.17L8.83 12L11 9.83L9.59 8.41L6 12l3.59 3.59zm3.41 1.42L18 12l-3.59-3.59L13 9.83L15.17 12L13 14.17z" fill="#626262"/><path d="M19 3h-4.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H5c-.14 0-.27.01-.4.04a2.008 2.008 0 0 0-1.44 1.19c-.1.23-.16.49-.16.77v14c0 .27.06.54.16.78s.25.45.43.64c.27.27.62.47 1.01.55c.13.02.26.03.4.03h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-7-.25c.41 0 .75.34.75.75s-.34.75-.75.75s-.75-.34-.75-.75s.34-.75.75-.75zM19 15v4H5V5h14v10z" fill="#626262"/></svg>

### Instalación <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 512 512"><path d="M393.87 190a32.1 32.1 0 0 1-45.25 0l-26.57-26.57a32.09 32.09 0 0 1 0-45.26L382.19 58a1 1 0 0 0-.3-1.64c-38.82-16.64-89.15-8.16-121.11 23.57c-30.58 30.35-32.32 76-21.12 115.84a31.93 31.93 0 0 1-9.06 32.08L64 380a48.17 48.17 0 1 0 68 68l153.86-167a31.93 31.93 0 0 1 31.6-9.13c39.54 10.59 84.54 8.6 114.72-21.19c32.49-32 39.5-88.56 23.75-120.93a1 1 0 0 0-1.6-.26z" fill="none" stroke="#626262" stroke-linecap="round" stroke-miterlimit="10" stroke-width="32"/><circle cx="96" cy="416" r="16" fill="#626262"/></svg>
* Instalar previamente npm y Node.js en tu computador.

* Ejecuta el siguiente comando en la terminal.
```js
$ npm i danielablancom-md-links 
```

### Uso <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32"><path d="M27 16.76V16v-.77l1.92-1.68A2 2 0 0 0 29.3 11l-2.36-4a2 2 0 0 0-1.73-1a2 2 0 0 0-.64.1l-2.43.82a11.35 11.35 0 0 0-1.31-.75l-.51-2.52a2 2 0 0 0-2-1.61h-4.68a2 2 0 0 0-2 1.61l-.51 2.52a11.48 11.48 0 0 0-1.32.75l-2.38-.86A2 2 0 0 0 6.79 6a2 2 0 0 0-1.73 1L2.7 11a2 2 0 0 0 .41 2.51L5 15.24v1.53l-1.89 1.68A2 2 0 0 0 2.7 21l2.36 4a2 2 0 0 0 1.73 1a2 2 0 0 0 .64-.1l2.43-.82a11.35 11.35 0 0 0 1.31.75l.51 2.52a2 2 0 0 0 2 1.61h4.72a2 2 0 0 0 2-1.61l.51-2.52a11.48 11.48 0 0 0 1.32-.75l2.42.82a2 2 0 0 0 .64.1a2 2 0 0 0 1.73-1l2.28-4a2 2 0 0 0-.41-2.51zM25.21 24l-3.43-1.16a8.86 8.86 0 0 1-2.71 1.57L18.36 28h-4.72l-.71-3.55a9.36 9.36 0 0 1-2.7-1.57L6.79 24l-2.36-4l2.72-2.4a8.9 8.9 0 0 1 0-3.13L4.43 12l2.36-4l3.43 1.16a8.86 8.86 0 0 1 2.71-1.57L13.64 4h4.72l.71 3.55a9.36 9.36 0 0 1 2.7 1.57L25.21 8l2.36 4l-2.72 2.4a8.9 8.9 0 0 1 0 3.13L27.57 20z" fill="#626262"/><path d="M16 22a6 6 0 1 1 6-6a5.94 5.94 0 0 1-6 6zm0-10a3.91 3.91 0 0 0-4 4a3.91 3.91 0 0 0 4 4a3.91 3.91 0 0 0 4-4a3.91 3.91 0 0 0-4-4z" fill="#626262"/></svg>

* Para hacer uso de la librería ejecuta el siguiente comando en la terminal de tu archivo.
```js
$ node tuarchivo.js tuarchivo.md
```
* Para ver el total de links y total de links únicos ejecuta el siguiente comando en la terminal.
```js
$ node tuarchivo.js tuarchivo.md --validate o node tuarchivo.js tuarchivo.md --v
```
* Para ver la cantidad de links únicos y totales ejecuta el siguiente comando en la terminal.
```js
$ node tuarchivo.js tuarchivo.md --stats o node tuarchivo.js tuarchivo.md --s
```
* Para ver estadísticas de tus links ejecuta el siguiente comando en la terminal.
```js
$ node tuarchivo.js tuarchivo.md --s -v o node tuarchivo.js tuarchivo.md ---stats --validate
```
* Para utilizar esta librería en un proyecto diferente, solo debes realizar la instalación y ejecutar el siguiente comando en la terminal.
```js
$ npx danielablancom-md-links tuarchivo.md 
``` 
* Sigue los comandos para ver el estado o las estadísticas de los links.

### Opciones 
* Si pasamos la opción -validate o -v, así es como deberías poder ver los resultados en la terminal. 

![Validate](https://i.ibb.co/XWqk65s/validate.jpg)


* Si pasamos la opción -stats o -s el output (salida) arrojará los datos del total de links y links únicos. 

![Stats](https://i.ibb.co/FBLQXry/stats.jpg)

* También podemos combinar -stats y -validate o -s y -v para obtener estadísticas que necesiten de los resultados de la validación.

![validate y stats](https://i.ibb.co/FJ7FCsp/validate-stats.jpgpg)

### Dependencias <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path d="M13.06 8.11l1.415 1.415a7 7 0 0 1 0 9.9l-.354.353a7 7 0 0 1-9.9-9.9l1.415 1.415a5 5 0 1 0 7.071 7.071l.354-.354a5 5 0 0 0 0-7.07l-1.415-1.415l1.415-1.414zm6.718 6.011l-1.414-1.414a5 5 0 1 0-7.071-7.071l-.354.354a5 5 0 0 0 0 7.07l1.415 1.415l-1.415 1.414l-1.414-1.414a7 7 0 0 1 0-9.9l.354-.353a7 7 0 0 1 9.9 9.9z" fill="#626262"/></svg>

Para poder llevar a cabo esta librería fue necesario instalar algunas dependencias fuera del entorno de node js. Como por ejemplo: 


- Módulo [chalk](https://github.com/chalk/chalk). La misma se utilizò para colocar colores a las respuestas del paquete por consola.

 - Módulo [marked](https://www.npmjs.com/package/marked). Compilador de bajo nivel para analizar el marcado sin almacenar en caché o bloquear durante largos períodos de tiempo.


 Fuera de node js se utilizaron las siguientes dependencias:

- Módulo [process](https://nodejs.org/docs/latest/api/process.html#process_process_argv) con `process.argv[]`. Para obtener la ruta del archivo ingresado por el usuario en la terminal.

- Módulo [path](https://nodejs.org/api/path.html#path_path_isabsolute_path). Para poder normalizar una ruta y obtener posteriormente la ruta absoluta.

- Módulo [fs.existsSync](https://nodejs.org/api/fs.html#fs_fs_existssync_path). Permite saber si la ruta ingresada existe.

- Módulo [fs.lstatSync](https://nodejs.org/api/fs.html#fs_fs_existssync_path). Permite conocer si la ruta ingresada pertenece a un directorio. 

- Módulo [fs.readdir](https://nodejs.org/api/fs.html#fs_fs_readdir_path_options_callback). Lee asincrónicamente todo el contenido que se encuentra dentro del directorio.

- Módulo [fs.readFile](https://node.readthedocs.io/en/latest/api/fs/). Lee asincrónicamente todo el contenido de un archivo.


### Autora

* [Daniela Blanco](https://github.com/danielablancom)
