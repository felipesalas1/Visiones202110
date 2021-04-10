# Visiones de la Investigación 202110, Maestría en Humanidades Digitales, Universidad de los Andes
# Anteproyecto de trabajo de grado

## Felipe Salas Noguera, código 201413117

## Fecha: enero 30 de 2021

## Título
**Algoritmos de recomendación de música: una mirada desde Colombia y la música emergente**

## Palabras clave
* Algoritmos de recomendación; Plataformas de Streaming (Apple Music, Spotify, Youtube Music); AI; Sesgos de los Algoritmos; Música Emergente; Filtro Burbuja

## Abstract




## Objetivo general

Con el uso de las API de las plataformas de streaming, crear una herramienta para conocer nuevos proyectos musicales de Bogotá. Esto con el fin de contrarestar el filtro burbuja y la baja diversidad de consumo de música causada por los algoritmos de recomendación usados en Spotify, Apple Music y Youtube Music. Con esto, podré identificar cómo los algoritmos de recomendación afectan el descubrimiento de proyectos musicales emergentes. 


## Lista de productos esperados 

1. * Aplicación web que permite a los usuarios agregar nueva música a sus cuentas de las plataformas de streaming
2. * Texto 

## Problema

Los algoritmos de recomendación, desde su concepción, están sesgados y siguen un modelo capitalista de busqueda de lucro. Esto ha provocado que baje la diversidad de contenido consumido en las plataformas de streaming. En consecuencia, los nuevos proyectos musicales tienen dificultad para ser descubiertos y que sean escuchados por más usuarios. 

- No estoy seguro si esto es más la hipótesis de trabajo que el problema.

## Hipótesis de trabajo

## Fuentes


**APIs**

Un posible inconveniente con el uso de las APIs es que estas pueden cambiar la cantidad y los datos que se pueden obtener de la plataforma. Por ahora, su uso es gratuito y permiten crear una cuenta de desarrollador para hacer uso de la herramienta. Sin embargo, se debe tener en cuenta los términos y condiciones del uso de las APIs y revisar que el proyecto sigue respetando el uso de las plataformas.

* Apple. Apple Music API | Apple Developer Documentation. https://developer.apple.com/documentation/applemusicapi/. Consultado el 9 de febrero de 2021.

* Google. “Youtube API”. Google Developers API, https://developers.google.com/youtube/v3.

* Spotify. Web API | Spotify for Developers. https://developer.spotify.com/documentation/web-api/. Consultado el 9 de febrero de 2021.


## Metodología

Para el desarrollo de este proyecto se usará un servidor web, el frontend va a ser en HTML y CSS y el back end, para ser compatible con los APIs de las plataformas de streaming, va a hacerse en JSON basándose en REST y en JS (estoy considerando Python). Para poder desplegar los primeros prototipos de la plataforma usaré la capa gratuita de Amazon AWS, la cual me permitirá, por un año, tener acceso a un servidor web en la nube para hacer las pruebas y prototipos.  
  
La plataforma consiste en recomendar nuevos proyectos musicales a los usuarios. Para hacer esto, se va a tener en cuenta su librería de música, las recomendaciones que da el algoritmo de las plataformas y la la base datos propia de proyectos musicales. El producto final es una playlist creada a la medida de cada usuario.  
  
Es importante tener en cuenta que las APIs pueden limitar el número de datos entregados por cada consulta, esto puede ser un problema al consultar la librería musical de los usuarios. Por lo anterior, es necesario recopilar información de proyectos musicales bogotanos de fuentes externas (fuentes propias, colectivos musicales de la ciudad como La Cara de Emer, El Enemigo, EMV –una rama del IDRD–, y bases de datos distritales de músicos), para después categorizarlas y hacer recomendaciones en grupos más pequeños. 



## Bibliografía anotada

El enlace de la bibliografía es este: https://www.zotero.org/groups/2803661/bibliografavisiones/library
