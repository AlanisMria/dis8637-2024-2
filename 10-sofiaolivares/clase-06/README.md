# clase-06

24 de septiembre 

# Diseño de interacción 

no se necesita tecnologia para realizar una buena experencia de usario.
uilizando distintos estados, momento en el tiempo en que una cosa existe una cosa de otra. se pueden conservar o cambiar los estados.
 "la forma sigue la función" relación con el esqueomorfismo. pensamieno proveninte de la bauhause. 
 en el mundo contemporaneo se cuestiona este concepto, la forma sigue a la forma, diseñar desde lo sensorial y lo estético.
 hurística: concepto aprendido por repetición, se realiza un consenso social de donde se ubican las cosas. 
 Forma sigue a la función interacción. función social. ref proyecto: prism 

no seguir el cocepto de usuario promedio, porque no existe, todas las personas tienen distintas caracterísicas. El usuario común. 
no diseñar para la funcionalidad y no para el comportamiento del usuario. 

## Patrones de diseño 

No causa duda el funcionamiento de algún disposiivo, por ejemplo, el botón de la ventana del auto, como subir y bajar, nadie se cuesiona su funcionamiento. Manera auomática, el usuario de adapta, cuando esto funciona se cumple el patrón de diseño.
Convención social, consenso social.

Qué pasa si falla, hay que hacerse cargo de el diseño de fallas. 
Responde a estados. 

Cuales son los patrones para cambiar de un estado a otro. Regla de comportamiento, a través de situaciones limitrófes 
No todos los elementos diseñados tienen que generar una interacción.

En el ámbito tecnológico no hay un límie físico, hay que diseñar comportamiento. 
Tener en cuenta para quienes estamos diseñando. Cuál es público objetivo. 

No solo como las cosas se ven, sino también como se coportan, la funcion, la forma, el comportamiento, tienen que conversar. 

Como diseñamos cuando los objetos están conectados a otra dispositivo 
ej: reloj conectado al celular.
Endomotica, objeto que a través de interfaces digitales que nos permite cotrolar o ver los estados. 
refrigeradores con pantalla. 

sacar prejuicios a la hora de diseñar, hay un usuario para todo. 
 Como hacer que no todo pase en pantalla, mirar que pasa más allá de una pantalla. 
 Ej: Cámara que me diga que está pasando, dispositivo que suene para tomar medicamento. 

Diseño de interacción no está limitado a la interfaz del dispositivo.
Pensar lo que la gente quiere, más alla de lo que la tecnología puede solucionar. 

 Diseño es político. 
 
## Exposición partituras inesperadas 
Felipe B 
Explora relación entre el arte y la música.
Respuesta a un fenomeno del siglo XX, Intención de hacer algo en vez de como lo hago. 
La música empezó a mutar, esta exposición celebra esto.
Visita el 15 de oct. 

## Apuntes 
continuación 

### API
API manera de counicarse entre máquinas, automatizar, condicionar ante algún suceso. 
API es una interfaz de programación de aplicaciones, regla de comunicación que hay entre nosotros y un sistema. 
Rapidapid app: 
pregunatar datos 
hay que tner control de acceso una llave "key"

## Arduino 
Wifi 
file - Examples - WifiS3 - ScanNetworks
setup
While: está pasando hasta que no y ahí sigue con el código

loop 
bit puede ser 0 o 1
byte
b minuscula bits
B mayuscula 
funcion te devuelve a un -1 que indica error o que no obtuvo conexión 
Wifi.SSDI: se le puede modificar e indicar otra acción que uno condicione. 

Serial: se imprime en el puerto serial, icono lupa que se encuentra en el lado superior de arduino IDE

serial print In da indicador al usuario que está pasando algo 
ListNetworks (): nombre fantasía, darle un nombre a una función, encontrar red de wifi 

serial.print: buscar detro del archivo

serial.println: salto de línea

\t : alinear información hacia abajo, ordenar

file - Examples - WifiS3 - WifiWebClient.ino
arduino_secret.h
#define SECRET_SSID "nombre wifi"
#define SECRET_PASS "clave" 

WifiWebClient.ino
setup
char server =   DNS ayuda a buscar la dirección IP de manera más automática, dando el servidor

IPAddres ip : Wifi.localIP el pc actua como router y le da una dirección IP al arduino 
puerto 80 es lo estándar de un servidor web

GET: 

void read_response 
interpreta, lo que le mandamos al arduino 
ordenar lo que va a salir en el puerto serial 

void loop 
!cliente.connected(): no conectado 
cliente: el que guía : arduino 

protocolo web: http://. fue creado para diseñar hiper texto, mandar paquetes completos, manera más lenta y pausada, para en caso de que falle  

udp: hartos datos, no para

mqtt: bajo costo procesamiento, seguro, filtra informacion, protocolo de red 

AP_ SimpleWebServer.ino 

arduino funciona como router, entrega dirección IP, aun no puede manejar multiples clientes.
hasta que se programe.
funcion como servidor.

el arduino manda de vuelta información en html 

GET / POST / PUT / DELETE :idioma html 








### osi model 
intercambio de red que funciona en las 7 capas 

1. Capa fisica por la cual viajan bits
2. Capa frames información se resive en conjuntos
3. Capa packets
4. 


