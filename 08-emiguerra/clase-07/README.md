# clase-07

hacer un dimmer con un LED con Arduino Cloud

- offline no significa que no reciba señal, significa que no tiene cargado un código
- network/ configure/ run
- intentar con el pin led

### Materiales necesarios:
- Arduino
- Cable de conexión USB
- LED

### Pasos:
1. Inicia sesión en [Arduino Cloud](https://cloud.arduino.cc/).
3. En el menú de Arduino Cloud, selecciona **Devices** y presiona **Add Device** para comenzar la conexión.
4. seleccionar arduino board
5. instalar el agente de arduino
6. tiene que estar funcionando en segundo plano
7.  Conectar con cable de datos  tu Arduino al puerto USB de tu computadora
8. Aparecerá la opción **Setup Device** donde deberás seleccionar tu placa Arduino.
9. Espera a que finalice la configuración de la conexión.
10. Una vez conectada la placa, ve a **Things** en el menú lateral izquierdo.
11. Presiona **Create Thing** para crear un nuevo "Thing" asociado a tu Arduino.
12. En **Associated Device**, selecciona tu dispositivo vinculado.
13. vincular el arduino con Network (colocar el nombre del wifi y la clave correspondiente )
14. Agrega una nueva variable presionando **Add**, en este caso, agrega la variable `Light` para controlar el encendido y apagado del LED.
15. ir a la opcion de dashboard preseionando mas deashboard
16. seleccionar add y elegir en la opcion widgets un slider (para manejar la intensidad del led )
17. presionar link variable y selccionar la variable utilizada
18. presionar link variable
19. En value range ir de 0 a 255 y seleccionar done 
20. Ve a la pestaña **Sketch** para asegurarte de que tu Arduino esté correctamente vinculado y listo para subir el código.

> **Nota**: Si ocurre algún error
> asegúrate de que el cable de conexión sea de cable 
> cambiar el navegador web preferentemente sea google chrome
> Que el arduino no este conectado ningun componente al momento de vincular el arduino al computador
> Reinicar la pagina de arduino cloud

## Tutoriales recomendados

Recomendamos empezar con el tutorial básico de encender un LED. Puedes encontrar los tutoriales recomendados en nuestro servidor de Discord.

### Experiencia del equipo

En el tutorial recomendado por **@morgan**, utilizamos el código propuesto. Lo modificamos ligeramente, y nuestra compañera **@alanis** logró encender el LED una vez, pero luego dejó de funcionar.

Gracias a la ayuda de **@paula**, quien revisó y modificó el código, lo compartió con todos nosotros y el problema se solucionó.

En mi caso, al principio tuve un problema con mi cuenta de Arduino Cloud, pero tras crear una nueva cuenta con otro correo, el proyecto funcionó sin problemas. Agradezco a **@paula** por su colaboración en este proceso.


## clase :
github.compus 
mitx circuito edx.org  (curso de circuito)
justjavascript.com 
chromium navegador 
safari: desarrollador no es muy bueno como usario si 
todo lo que puede pasar que no funcione el arduino:
navegador 
cable ( hay cables que solo es para cargar y no para datos)
reiniciar la pagina de arduino 
tener conectado unos comonente antes de vincular arduino 
bootlother 
watt:unidad de potencias 

## proyecto de paula :
servoEasing.h (para que realize mas delicado la funcion )
delay estorpese la funcion del servo motor 
servo motor azule engranaje de plastico se atraba menos fuerza , engranaje metalico mejor 
diagrama de flujo es impornate realizar (es paso a paso) diagrma de estado (abierto y cerrado ) con condiciones al medio activa una transicion (nada es intataneo )
ejmeplo: aumenta la luz o la rampa del casco 
![texto](./diagrama.jpg)
estados plumon:
inicio cuando empiza a importa el plumon (abierto o encuntra el plumon)
final( cerrado o soltar el plumon)
condicion es la accion (sacar la tapa ) sigueinte estado es escribir 

video : unity 1 animator controller beginner tutorial 
any state (cualquier estado )
si es cualquier estado puede pasar de close a 
ver: animator controller unity character (personajes con estados)

## proyecto de andres:
Material didactico(astronomia): Planetas y s.solar 
construccionismo (paradigma forma de aprender es aprender con las  manos y modificar el entorno )
gamificacion(ganar puntos ,sentivar a las personas a participar ) no material mas como personal 
### naves para recorrer el sistema solar (uno de los proyecto)
tipos de jugadores 
killers:
sociales:relacionarse con otras personas
exploradores : aporximarse a nuevas cosas 
creadores : expresarse su vicion y explasamarla 

inicio : exploracion 
(creacion)
desarrollo
(climax): ganar ,lograr 
final social coop

material ,creación de misiones, rellenar una guia (coperativa con el profesor) vitacora de viaje expeerimentacion con el material, ganar ensignia , general en conjunto se unen en grupos comparte naves y conocimiento crea una guia en la vitacora 

produccion : que tecnologia me puede servir 
chip sp32 (pes muy bueno)
importante de su proceso: no sabe cuanto es la dimencion para conectar  entonces lo fabrica aparte   

### clase
octube para diseñar un proyecto (conceptual , interacion planificaicon de estados componente y la presentacion 
3 sesiones ) preguntar a la gente algo , pedir una opion que
octubre 6 proyectos 
el examnen es un sistema de manifestacion opinion del soberano 
interaccion rapida 
representarla (led, un sonido,una bandera, un casco que abre o cierra)
general y capturar(con o sin piña ) 
pagina luciddreams (ofrese experiencia de vida virtual)
chen-yihan.com 
xxx.tiri.xxx
que sea un artefacto 
referentes de proyecto que queremos hacer 
como votar
the guardian.com (
gabe barcia colombo
ready made  
hacerlo grande / hacer muchas / hagalo rojo (llama la atencion)

tarea: cual es dilema quieres plantear 
leyes -prioridad
etica-discriminacion
emociones - marcas (cual emocion ,incomodo,frutacion )
consumo-sentido
ambiente-resitencia
intensidad-autopercepcion
incomodo-paparazi (
## inmput
pesa: celda de carga
lanzar 
distancia: ultra sonido tof laser 
usar o ponerse 
aro azar 
tegistro personal
calor t°
tiempo haciendo 
## output
robot 
reloj gigante 

> *Apuntes referenciados desde el repositorio de @T1ar3*
