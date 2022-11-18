---
aliases: [Clase taller un mapa simple en Qgis]
tags: icaba sig
author: Marcos Gustavo Cortina
date: 2022-10-26 20:32
source: https://
comments: Taller. Un mapa simple en QGis
location: [-34.659261,-58.649668]
---
#todo 
- [ ] Taller. Un mapa simple en QGis.(@2022-11-18 12:31)
 ___
# QGis 
## Taller. Un mapa simple en QGis
---
| [Página Web de Cartografía](https://www.marcosgustacocortina.com) |
Esta página: https://marquein.github.io/Web_QGis/

## Objetivos:
1. Dar las herramientas "*superbásicas*" para que cualquier persona pueda hacer un mapa a la medida de sus necesidades con los elementos básicos. El producto es un .pdf georreferenciado.
2. **El producto: puntos y líneas sobre un mapa de Google o de Open Street Map.**
3. Entusiasmar y difundir la cartografía. De ser posible crear una comunidad dentro del CABA/ICABA para cartografiar en conjunto.

## Temario 
- **Instalación** de [QGis](https://qgis.org/es/site/) (preferiblemente de antemano). Tener en cuenta que pesa 1 G y demanda una pc más o menos moderna. Cuanto más procesador, disco ssd y ram, más fluido va a correr.
- **¿Qué es QGis?** ¿Para qué sirve?¿Qué se puede hacer?
- **Descripción general de los partes del entorno visual** de QGis. Paneles. Menús.
- **El Espacio de Trabajo.** El lienzo. Proyecciones.
- **Mapa de fondo.** Instalación de Plugin.[[plugins]]. *QuickMapService* [^material]
- **Capas:** puntos, líneas y polígonos. Tabla de atributos.
- **Tipos de archivos** - extensiones-. Vectoriales vs. raster.
	- kml: [Blog que explica la estructura interna](https://developers.google.com/kml/documentation/kml_tut?hl=es) (ya que le gusta que vea como es el contenido del kml). Recordar como lo usábamos en Google earth.
	- shp.
	- geojson.
	- geopackage
	- raster: tiff
- **Digitalización**
	- Digitalizar en Google Earth.
	- Importar el kml y exportarlo a un formato más apto para Qgis.
	- La complejidad de digitalizar en QGis.
- **Producción del mapa**.
	- Tamaño del lienzo SA3.
	- Grilla de coordenadas.
	- Exportación. pdf y svg.
- **Mostrarles GitHub. Nuestra idea.**  
	- Mostrar la Página. Necesitan usuario. Pueden descargar porque los repositorios son públicos.
	- Colaboración pública hasta 100 megas.
	- Privada hasta 1 Tera.
	- Concepto colaborativo. GitHub. Contra: no sincroniza directamente con QGis.

___
## Propuesta avanzada para la próxima.
Dar un pantallazo de lo que se puede explicar en próximos encuentros.

- Trabajo con Modelos de Elevación Digital (DEM).
- Obtener curvas de nivel.
- Calcular pendientes.
- Cortar capas por máscara.

___
## Nuestro Proyecto
[GitHub OrientaciónCABA](https://github.com/OrientacionCABA)
Contarle las posibilidades para que el que se entusiasme vaya por más.

### Inquietud:
- [[@Gabriel Boubenicek]] que quería bajar los puntos de los _cerros_ y _tracks_ para rutas de montaña.
- Del mismo modo con [[@Rodrigo Sanchez]] queríamos distribuir un poco el trabajo para hacer nuestros mapas. 
- Lo interesante es como con la misma materia prima - los mapas vectorizados- podemos producir dos mapas completamente distintos y con identidades distintas.

### Objetivos concretos:
- Digitalizar/ relevar cerros - explicar diferencia de los término-.
- Digitalizar/ relevar poi.
- Generar un grupo de colaboración.

### Desafío:
- Crear comunidad GitHub. Para el que solo quiera subir y bajar archivos. 
	- ¿Qué es GitHub?
	- La Web.
	- GitHub Desktop.
		- Repositorios.
		- Ramas.
		- Permisos sobre el repositorio. Admisitrador/editor/lector.
		- Comit.
		- push/pull
		- fork
	- Beneficios con respecto a [_QfieldCloud_](https://qfield.cloud/) y sus desventajas también.
- Plug in QGis Cloud.
	- El plugin en QGis.
	- La Web.
	- Qfield en el celular.


___
[^material]: Habría que preparar un set de capas ya armadas para usar como ejemplo. Tenerlas en una carpeta para compartir. Se las puede alojar en un repositorio para que se vayan amigando con la plataforma.