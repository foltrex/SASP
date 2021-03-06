# SASP
Scientific Adaptative Searching Platform

El proyecto consiste en realizar un buscador de material relacionado con la ciencia (especificamente: física). El buscador debe poder encontrar material en toda la web a partir de palabras claves ingresadas por un usuario buscador y además ajustarse a uno de los cuatro tipos de aprendizaje de Kolb: asimilador, divergente, convergente y acomodador.

El buscador funciona mediante calificaciones a los links que visitan los usuarios. La calificación de los links será el promedio de la calificación que le den los usuarios de cierto tipo, es decir, habrá 4 calificaciones distintas dependiendo del tipo.
Los enlaces con mayor calificación se mostrarán primero.
## Requerimientos

* [Python 3.6.1](https://www.python.org/)
* [MySQL](https://www.mysql.com/)
* [PyMySQL](https://github.com/PyMySQL/PyMySQL)
* [Flask](http://flask.pocoo.org/)
* [GoogleApiCliente](https://developers.google.com/api-client-library/python/start/installation) (Python)

## Ejecución
1.- Tener instalados todos los requerimientos

2.- Descargar y extraer el repositorio

3.- Dirigirse al directorio ../SASP/Programa/Vista

4.- Ejecutar en Python el archivo server.py

5.- Seleccionar el link en consola o dirigirse a la dirección http://127.0.0.1:5000/ (localhost) en un navegador web actualizado

6.- Se abrirá la vista principal del sistema y podrá realizar búsquedas
