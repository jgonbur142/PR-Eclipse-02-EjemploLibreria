## Reflexión  

* ¿Qué pasaría si exporto el proyecto a un .zip y se lo paso a un amigo o me lo llevo al ordenador de casa? ¿Funcionaría? Razona la respuesta.

  - Sí, al exportar el proyecto entero las rutas de ejecución son las mismas.
 
* ¿Qué pasaría si eliminas el archivo .jar de la carpeta lib? (puedes moverla a otro directorio para probarlo) ¿Qué ha pasado y por qué?

  - Que no compilaría el programa, ya que no encontraría la librería necesaria y no podría importarla.

* Y si agrego la librería con Add External JARs.... ¿Observas alguna diferencia en la configuración del Build Path? ¿Crees que si lo exporto a .zip y se lo paso a un compañero le funcionaría?

  - De este modo ya no se marcan errores de sintaxis pero sigo sin poder ejecutar el programa. En el Build Path me aparece el primer joda-time como missing y debajo el joda-time que he añadido con Add External JARs.
 
* ¿Por qué no es recomendable usar Add External JARs… en proyectos que vas a compartir?

  - Porque la ruta que se está usando en mi sistema no será la misma que se use en el de la persona que lo descargue y ejecute.
