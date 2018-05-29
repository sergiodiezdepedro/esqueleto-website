# Entorno de trabajo con Gulp, Sass y Pug

Este proyecto es tan sólo un entorno de trabajo en el que me siento cómodo y produzco con más eficacia. He incluido un esqueleto de website realizado con Pug y con unos pocos toques de CSS con Sass para que se pueda verificar y probar el funcionamiento de la herramienta.

Gulp es el gestor de tareas que se encarga de borrar por completo el contenido de la carpeta de producción al inicio de la sesión de trabajo, compilar Pug y Sass, optimizar las imaǵenes, depurar y minimizar el CSS final, concatenar los archivos JS y mimimizar el de producción, mover todos los archivos necesarios a la carpeta de producción (*dist/*) y levantar un servidor de desarrollo.

La tarea que realiza todo el trabajo es, simplemente, **gulp**.