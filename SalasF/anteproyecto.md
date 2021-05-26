# Visiones de la Investigación 202110, Maestría en Humanidades Digitales, Universidad de los Andes
# Anteproyecto de trabajo de grado

## Felipe Salas Noguera, código 201413117

## Fecha: Mayo 26 de 2021

## Título
**Algoritmos de recomendación de música: una reflexión desde a estética a **

## Palabras clave
* Algoritmos de recomendación; Plataformas de Streaming (Apple Music, Spotify, Youtube Music); AI; Sesgos de los Algoritmos; Música Emergente; Filtro Burbuja

## Abstract

Con la aparición de las plataformas de streaming de música, el funcionamiento de la industria musical y el consumo de música ha cambiado radicalmente. El descubrimiento de nueva música ha pasado de ser influenciada por emisoras de radio, o por escuchar nuevos proyectos en tiendas de discos, a ser dictadas, en su mayoría, por algoritmos de recomendación (algoritmos BART) que hacen parte de las plataformas de streaming. Con esto, los algoritmos se convirtieron en los curadores personales de música para los usuarios. La experiencia que cada oyente tiene en las plataformas de streaming está mediada por un algoritmo que decide que música poner en aleatorio, o que canciones mostrar en las listas de reproducción para descubrir nueva música.  

En consecuencia, los algoritmos disminuyen la diversidad de consumo de música, y tienen sesgos que afectan a proyectos musicales que no aportan al afán de lucro de las plataformas de streaming. Este proyecto, se va a basar en dos partes, en a primera, se investigará sobre la estética de los algoritmos, los sesgos y el fitro burbuja; en la segunda, se va a desarrollar una plataforma donde usuarios de Spotify van a poder recibir recomendaciones de proyectos musicales bogotanos que, probablemente, el algoritmo no les va a recomendar en otras situaciones. Con esto, busco comprobar si es posible que, usando el mismo algoritmo de Spotify y su API, se logre bajar los sesgos y aumentar la diversidad de consumo de música en esta plataforma de streaming.  


## Objetivo general

Investigar sobre la estética de los algoritmos, sus sesgos, el filtro burbuja, y cómo son los mediadores de a experiencia en las plataformas de streaming. Con la finalidad de identificar cómo estos aspectos afectan el descubrimiento de proyectos musicales emergentes que no aportan al afán de lucro de las plataformas de streaming.


### Objetivos Específicos

1. Investigar los aspectos estéticos de los algoritmos y ver cómo estos hacen parte de la experiencia musical en el siglo XXI
2. Medir en que forma la aplicación web contrarresta el sesgo y la baja diversidad de consumo del algoritmo dde Spotify
3. Estudiar cómo el algoritmo de Sppotify afecta a la escena musical emergenten de Bogotá


## Lista de productos esperados 

1. * Reflexión sobre la estética de los algoritmos de los resultados de la plataforma
2. * Aplicación web que permite a los usuarios agregar nueva música a sus cuentas de las plataformas de streaming

## Problema

Los algoritmos de recomendación, desde su concepción, están sesgados y siguen un modelo capitalista de busqueda de lucro. Esto ha provocado que baje la diversidad de contenido consumido en las plataformas de streaming. En consecuencia, los nuevos proyectos musicales tienen dificultad para ser descubiertos y que sean escuchados por más usuarios. 

¿Existe la posibilidad de crear una herramienta que ayude a contrarrestar el filtro burbuja y la baja diversidad de consumo en Spotify?


## Hipótesis de trabajo

Los algoritmos de recomendación tienen sesgos, disminuyen la diversidad de consumo y afectan el consumo de música que no aporta a su afán de lucro. Sin embargo, usando el API de Spotify se puede cambiar el comportamiento del algoritmo y contrarestar sus efectos negativos en el consumo de música.

## Fuentes

- Base de datos de músicos Bogotanos, tengo acceso a la de La Cara de Emer, legalmente puedo usar los datos. puedo solicitar el de el IDRD por medio de un derecho de petición. y hacer una convocatoria (revisar si tengo que hacer algo con el cómite de ética)

**APIs**

Un posible inconveniente con el uso de las APIs es que estas pueden cambiar la cantidad y los datos que se pueden obtener de la plataforma. Por ahora, su uso es gratuito y permiten crear una cuenta de desarrollador para hacer uso de la herramienta. Sin embargo, se debe tener en cuenta los términos y condiciones del uso de las APIs y revisar que el proyecto sigue respetando el uso de las plataformas.

* Apple. Apple Music API | Apple Developer Documentation. https://developer.apple.com/documentation/applemusicapi/. Consultado el 9 de febrero de 2021.

* Google. “Youtube API”. Google Developers API, https://developers.google.com/youtube/v3.

* Spotify. Web API | Spotify for Developers. https://developer.spotify.com/documentation/web-api/. Consultado el 9 de febrero de 2021.


## Metodología

Este proyecto se divide en dos partes, una teórica y una práctica. Para la primera parte, estudiaré los aspectos estéticos y los sesgos del algoritmo de recomendación de música de Spotify. Esta sección será la base para la creación de la plataforma, y se basa en la hipótesis que es imposible que los algoritmos de recomendación no estén sesgados y contribuyan a filtro burbuja, más que todo cuándo están al servicio de la búsqueda de lucro. 
  
Para el desarrollo de la segunda parte, se usará un servidor web, el frontend va a ser en HTML y CSS y el back end, para ser compatible con los APIs de las plataformas de streaming, va a hacerse en JSON basándose en REST y en JS (estoy considerando Python). Para poder desplegar los primeros prototipos de la plataforma usaré la capa gratuita de Amazon AWS, la cual me permitirá, por un año, tener acceso a un servidor web en la nube para hacer las pruebas y prototipos.   
   
La plataforma consiste en recomendar nuevos proyectos musicales a los usuarios. Para hacer esto, se va a tener en cuenta su librería de música, las recomendaciones que da el algoritmo de las plataformas y la base datos propia de proyectos musicales. El producto final es una playlist creada a la medida de cada usuario.   
   
Es importante tener en cuenta que las APIs pueden limitar el número de datos entregados por cada consulta, esto puede ser un problema al consultar la librería musical de los usuarios. Por lo anterior, es necesario recopilar información de proyectos musicales bogotanos de fuentes externas (fuentes propias, colectivos musicales de la ciudad como La Cara de Emer, El Enemigo, EMV –una rama del IDRD–, y bases de datos distritales de músicos), para después categorizarlas y hacer recomendaciones en grupos más pequeños. 


- Usar Knime y tensor flow para el manejo de datos



## Bibliografía anotada

El enlace de la bibliografía es este: https://www.zotero.org/groups/2803661/bibliografavisiones/library

## Comentarios de mis compañeras y de Nicolás

> Pensar en la divuglación con personas de la Escena. mirar con la Cara de Emer!! 
> Si voy a alcanzar a salir de eso

> - Salir del filtro burbuja 
> - En que medida se puede salir 
> - comparar papers sobre los datos de los algoritmos. 
> - Echarle cabeza si quiero llegar a la plataforma o desde lo investigativo


## Comentarios presentación

> Añadir lo que quiero hacer, mis objetivos
> Añadir que es lo que busco 
> Aclarar si voy a poder responder las dos preguntas, quizá la segunda solamente por encima
> Añadir una diapositiva con la hipotesis y poner fuentes 
> No tiene que ser tan rigido, puedo añadir más partes
