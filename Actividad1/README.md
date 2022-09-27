# -
1. Crea un repositorio para subir todas las actividades de esta asignatura con el
nombre despliegue-de-aplicaciones-web.
.
2. Crea una carpeta en tu repositorio llamada “Actividad 1” y dentro crea un archivo
README.md con la solución a los siguientes ejercicios.
.
3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
# -datos sensibles que se envían:

# -Al loggear en moddle inspeccionas antes de entrar, y luego en Network/index.php ---> payload y headers.

# -https://gimbernat.esemtia.net/moodle/login/index.php
# -anchor: 
# -logintoken: b14wO8O341oIC6TG78PPe7f5XBeqBZ7V
# -username: jgamarra@campus.eug.es
# -password: "******"

4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP,
UDP, e IP?
# -En TCP el puerto por defecto, para un servidor HTTP en ordenador, es el puerto 80. Se pueden usar otros puertos como el 8000 o el 8080.
¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP?
# -Opera en la capa de red OSI o de Internet en TCP/IP y es un protocolo no orientado a conexión, por lo que en definitiva se encarga de llevar de datos de un punto a otro.
UDP:
# -UDP pertenece a la familia de protocolos de Internet, por lo que debe clasificarse en el nivel de transporte y, en consecuencia, se encuentra en una capa intermedia entre la capa de red y la capa de aplicación.

5. ¿Cuál es el significado de la siguiente respuesta de un servidor?
HTTP/1.1 302 Found
Location: http://www.example.com/test/index2.php

# -El código de estado de redirección HTTP 302 Found indica que el recurso solicitado ha sido movido temporalmente a la URL dada por las cabeceras Location (en-US).

6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.
# - www.google.com


