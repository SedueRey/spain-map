# Mapa interactivo de España
Mapa vectorial de España interactivo creado a partir de un mapa SVG y la librería RaphaëlJs.

## Forked

Este repositorio está realizado a partir de la labor de [Javier Toledo](http://https://github.com/javiertoledo/) en [este repositorio](http://https://github.com/javiertoledo/spain-map). 

## TODO

Quiero separar toda la definición de las `paths` de las provincias a un fichero aparte y cargarlo asíncronamente para que mejore la carga de la web en la que se encuentre el mapa y pueda ser enviado como `GZip` desde el servidor. Se mejoraría de 400KB a 99KB el envío y, sobre todo, de 483KB a 2KB la carga de la librería en primera instancia, después el usuario ya puede esperar con un mensaje de carga.