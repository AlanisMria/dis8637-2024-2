# Avances 

He estado dejando taller muy de lado por temas personales y otras cosas y me arrepiento, je

## Objetivo del día de hoy: Conectar Arduino con p5.js

Estuve viendo como hacer todo y llegué a partes en las que no entendí nada de nada. 
Viendo un tutorial en youtubr, entendí muchas cosas y me acordé de muchas otras que vimos en la clase de wifi. 
Básicamente, para hacer que arduino interactúe con p5, hay que hacer un puente ya que, al estar ejecutando p5 en la web, existen limitaciones de seguridad entonces, la comunicación serial entre estos dos es imposible (cuek). 

Lo que si se puede hacer son los socket, los cuales permiten que los programas se comuniquen entre sí vía wifi o por el mismo pc. Normalmente para esto se utiliza Node.js pero, según el caballero del tutorial, se puede hacer directamente a la web.

Lo primero que se debe hacer es conseguir la aplicación serial p5 [link](https://github.com/p5-serial/p5.serialcontrol/releases/tag/0.1.2), luego de eso se abre la app que funcionará como puente entre el arduino y p5, revisar el puerto en el que esta conectado el arduino con eso se ve la info del sensor que él estaba usando. Siempre y cuando esté conectado y abra, el programa sirve como puente a través de un socket interno que se puede usar en el p5, usando la biblioteca en serie p5,, dentro de p5 en el archivo index.html se vinculan las bibliotecas. 
