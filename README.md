Para iniciar el proyecto deberá situarse en la carpeta raíz y ejecutar el comando npm install
Cuando éste acabe, ejecutamos npm run serve


He creado un proyecto usando vue3 y una librería de componentes llamada quasar que usa por defecto Material Design, para el diseño me he basado en el ejemplo que se daba en la prueba aunque, he desactivado los links que no se requerían y que son solo estéticos.
Para las routas he usado vue-router 4.
Para las store he usado pinia, ya que es lo nuevo que se está implementando con vue 3, de hecho se considera según el creador de vue la nueva versión de vuex 5.

He asumido que hay una session activa.

Para la api, simplemente he generado funciones que interactuan con las stores y muestran los datos, por este motivo no he usado la biblioteca de axios, ni he generado una carpeta de services.

Según leía la prueba he considerado que la mejor manera de gestionar las licencias y ver el historial de pagos sería mediante tablas interactivas para el usuario.

A la hora de crear una nueva licencias pensé en un modal interactivo pensando en lo cómodo que sería en una versión mobile.

Para el tema de caducar las licencias y el autorenew, solo están su aspecto visual, ya que considero que esa funcionalidad debería estar en un backend.(Se crearían jobs programados para lanzarse cada X tiempo y sería muchísimo más fácil de gestionar).
