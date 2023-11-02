# Mi aplicacion 
Aplicando lo aprendido en los cursos de arquitectura limpia

## Introduccion(Explicacion)

Hay que entender los principios de la arquitectura limpia implemnetado a flutter, el negocio es el que define las entidades y los casos de uso del proyecto 

### Capa de dominio 

Las capas de dominio es donde guardamos los json de respuesta que nos regresan el back end podemos guardar las capas de lo que queremos hacer, tambien se guardas los casos de uso que tienen como dependencia la puerta de enlace que hace con las petiiciciones esto permite flexibilidad en cuanto a los cambios del front ya que no habria que cambiar mucho.

### Capa de insfraestructura

Las infreacturas es donde se guardar las conexiones con repositorios y APIS esta seccion se guarda en una carpeta de driver_adapter donde guardaremos todas las conexiones como por eljemplo firebase y tambien debemos incluir las carpetar de helpers en la sub carpeta de common donde hacemos a coversion de json a una etindad, tambien en el album guardamos el album_mapper donde haremos la conversion de JOSN a una clase, tambien se creara un una carpetta de driver adapater donde gestionamnos la conexion con las distintanta APIS 

### Capa de UI

La arquitectura limpia no dice como esta estructurado tu proyecto, casi siempre se le suele implementar todo el tema de la arquictetura limpia en el proyecto 

### Capa de configuracion 

la capa de configuracion no debe estar ligado fuertemenete a las otras capas esto ayuda con la inyeccion de dependencias 