#BD PROCESSING

##La practica de procesamiento de datos de Big Data que utiliza una arquitectura lambda para el procesamiento de datos 
recolectados desde antenas de telefonía móvil. El proyecto incluye tres capas: Speed Layer, Batch Layer y Serving Layer.
Las tecnologías utilizadas para cada capa incluyen Spark Structured Streaming, Apache Kafka, Google Compute Engine, Spark SQL, 
Google Cloud Storage, Google SQL (PostgreSQL). El proyecto utiliza un simulador para enviar información sobre 5 antenas y 20 
dispositivos móviles a Kafka. Para configurar el Speed Layer, el proyecto crea y configura una instancia en Google Compute Engine
para poder hacer funcionar un broker de Apache Kafka, donde se recibirán los mensajes en tiempo real de las fuentes 1 y 2. 
Un simulador de datos es utilizado para producir datos, y la instancia de Google Compute Engine es capaz de consumir estos datos.





###NOTA: La practica realizada tuvo problemas (no de codigo) sino al parecer un error en la fecha colocada donde no habian datos. despues de haber usado 2
cuentas GCLOUD no logro obtener otra prueba gratis y por motivos personales aun no he podido realizar el superset ni las capturas la cual en la 
medida de lo posible lo realizare ya que ha sido una de las practicas con la que mas me pelie y que me gusto. Un gran saludo.


proxima actualizacion....
