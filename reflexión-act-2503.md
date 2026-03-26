# Actuvidad guiada 25/03 - Reflexión
_solo hice esta parte porque siento que esta actividad es idéntica a la AE-4_

__Preguntas de reflexión:__

_1. ¿Qué ventajas ofrece Django ORM frente a la modificación manual de esquemas
en SQL?_
      Las venntajas que tiene el uso del ORM de Django son:
      - uso de un solo idioma para hacer consultas (en este caso Python)
      - no se tiene que recurrir a una aplicación externa para crear una tabla para albergar datos
      - (opinión personal) los procedimientos y comandos a utilizar son más simplificados, a pesar de que en SQL son fáciles de entender por su literalidad.

_2. ¿Qué riesgos evita el uso de migraciones incrementales?_
      Las migraciones incrementales reducen el riesgo de que una aplicación o el proyecto completo puedan presentar inconvenientes por algún cambio ya migrado. El ritmo parcelado de las migraciones y el hecho de que todas las migraciones realizadas "coexistan" en un directorio facilitan el manejo de las modificaciones en caso de existir un problema.

_3. ¿Por qué es importante versionar los archivos de migración en un proyecto
compartido?_
        Porque así se puede volver a una versión anterior ya sea para deshacer un cambio por completo o reemplazar una contribución por otra adición al proyecto. Al tener números y una descripción concisa en el nombre de archivo es fácil identificar los cambios a revisar y/o modificar.
