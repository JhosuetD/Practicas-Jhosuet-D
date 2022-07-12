# Practicas-Jhosuet-D
## Practicas Pre Profecionales con Aplicaciones Web
### Proyecto : Consumo de una API | Landing Page : Vanila JS 
En este repositorio encontraran los informacion necesaria sobre el proyecto.
Utilizaremos las siguientes herramientas: JavaScript, Node JS, Postman, HTML, CSS-GRID Flex, Responsive Desing

#### Información Previa 
## Qué es una API?
El término API es una abreviatura de Application Programming Interfaces, que en español significa interfaz de programación de aplicaciones. Se trata de un conjunto de definiciones y protocolos que se utiliza para desarrollar e integrar el software de las aplicaciones, permitiendo la comunicación entre dos aplicaciones de software a través de un conjunto de reglas.
Así pues, podemos hablar de una API como una especificación formal que establece cómo un módulo de un software se comunica o interactúa con otro para cumplir una o muchas funciones. Todo dependiendo de las aplicaciones que las vayan a utilizar, y de los permisos que les dé el propietario de la API a los desarrolladores de terceros.
 
## Códigos de Estado de Respuesta HTTP
# +400 Bad Request 
La respuesta de código de estado del Protocolo de Transferencia de Hipertexto (HTTP) 400 Bad Request indica que el servidor no puede o no procesará la petición debido a algo que es percibido como un error del cliente

# 401 Unauthorized 
El código de error HTTP 401 indica que la petición (request) no ha sido ejecutada porque carece de credenciales válidas de autenticación para el recurso solicitado. Es similar al estatus 403, pero en este caso , la autenticación si es posible.

# 402 Payment 
Required Este código de respuesta está reservado para futuros usos. El objetivo inicial de crear este código fue para ser utilizado en sistemas digitales de pagos. Sin embargo, no está siendo usado actualmente.

# 403 Forbidden
El error 403 Forbidden es un código de respuesta HTTP el cual indica que el servidor ha recibido y ha entendido la petición, pero rechaza enviar una respuesta.

# 404 Not Found 
El codigo de error HTTP 404 Not Found (404 No Encontrado) de respuesta de cliente indica que el servidor no puede encontrar el recurso solicitado. Vinculos que conducen a una pagina 404 son normalmente llamados vinculos rotos o vinculos muertos, y pueden estar sujetos a Enlace Roto.

## Node JS
Node.js es un entorno de ejecución de un solo hilo, de código abierto y multiplataforma para crear aplicaciones de red y del lado del servidor rápidas y escalables. Se ejecuta en el motor de ejecución de JavaScript V8, y utiliza una arquitectura de E/S basada en eventos y sin bloqueos, lo que la hace eficiente y adecuada para aplicaciones en tiempo real.


## Método GET 
El método GET se utiliza para solicitar la URL de un servidor web para recuperar los documentos HTML. Es un método convencional para que los navegadores entreguen la información que se cuenta como parte del protocolo HTTP. El método GET representado en forma de URL, para que pueda ser marcado como favorito. GET es ampliamente utilizado en los motores de búsqueda. Después de la presentación de una consulta por parte del usuario al motor de búsqueda, el motor ejecuta la consulta y da la página resultante. Los resultados de la consulta se pueden establecer como un enlace (marcado como favorito).

El método GET permite la generación de anclajes, lo que ayuda a acceder al programa CGI con la consulta sin el uso del formulario. La consulta se construye en un enlace, de modo que cuando se visita el enlace, el programa CGI recuperará la información adecuada de la base de datos.
El método GET tiene algunos problemas de seguridad porque los datos insertados están visibles en la URL. Solo se puede pasar una cantidad restringida de datos a través de un método GET, ya que la longitud de la URL que puede atravesar un navegador puede ser de mil caracteres.

Otro problema relacionado con el método GET es que no puede tratar con idiomas extranjeros. No se sugiere utilizar el método GET, pero aún cuando los atributos del método no están definidos, el método GET se usa como predeterminado.

## Método POST
El método POST es adecuado en la condición en que puede pasar una cantidad significativa de información. Cuando un servidor recibe la solicitud mediante un formulario que emplea POST, continúa "escucha" la información que queda. En palabras simples, el método transfiere toda la información relevante de la entrada del formulario instantáneamente después de que se realiza la solicitud a la URL.

El método POST necesita establecer dos contactos con el servidor web, mientras que GET simplemente hace uno. Las solicitudes en el POST se gestionan de la misma manera que en el método GET, donde los espacios están representados en el signo más (+) y los caracteres restantes están codificados en el patrón de URL. También puede enviar los elementos de un archivo.

# Conclusión
Los métodos GET y POST se utilizan para enviar los datos al servidor, y la principal diferencia entre ellos es que el método GET agrega los datos al URI definido en el atributo de acción del formulario. A la inversa, el método POST adjunta datos al cuerpo solicitado. El uso del método GET no es apropiado cuando se debe completar la información confidencial en el formulario. El método POST es útil cuando el usuario requiere completar las contraseñas u otra información confidencial.
