# Entrega 1

## Estructura

* .graddle -> Contiene archivos necesarios para la ejecución.
* entrega1 -> Contiene imágenes que forman parte de la entrega 1, relacionadas con los mapas de contexto y los eventstorming realizados.
* src/cml
   * dominios -> Contiene los fragmentos de código para detallar los dominios del proyecto. Dentro de cada archivo de dominio encontrará los subdominios que contiene cada uno.
   * mapas_contexto -> Contiene los fragmentos de código para detallar los mapas de contexto. Este folder contiene 2 folders dentro: 
      * as_is -> Contiene mapas de contexto actualmente el sistema.
      * to_be -> Contiene mapas de contexto con su respectivo rediseño.
* .gitignore -> Archivo de detalle de archivos que no serán tomados en cuenta en git.
* .gitpod.Dockerfile -> Archivo necesario para ejecución.
* .gitpod.yml -> Archivo necesario para ejecución.
* build.gradle -> Archivo necesario para ejecución.
* package-lock.json -> Contiene información de la app y los packages ya instalados.
* README.md -> Guía

## Ubicaciones de documentos a revisar

* Documentación de dominios y sub-dominios: src/dominios
* Documentación del lenguaje ubicuo:
    * flujo as-is: entrega1/event_storming_as_is.jpg
    * flujo to-be: entrega1/event_storming_to_be.jpg
* Documentación de contextos acotados:
    * imágenes:
        * mapas de contexto as-is: entrega1/mapas_contexto_as_is.png
        * mapas de contexto to-be: entrega1/mapas_contexto_to_be.png
    * fragmentos de código:
        * mapas de contexto as-is: src/cml/mapas_contexto/as_is/eventos_dominio.cml
        * mapas de contexto to-be: src/cml/mapas_contexto/to_be/eventos_dominio_to_be.cml
