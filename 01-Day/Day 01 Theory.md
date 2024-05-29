## Que es redes computadoras?
Es una red digital de telecomunicaciones que permite que los nodos compartan recursos

## Que es un nodo?
Puede ser un:
1. router
1. switch
1. firewall = Existe como software en una pc o hardware indpendiente 
1. server = Puede ser IBM, DELL
1. client = Puede ser una laptop, celular

> Los servidores y clientes tambien conocidos como "endpoints" o "endhosts"

Dos PC's conectadas forman una red simple

## Que es un Cliente:?
Es un dipositivo que accede a un servicio puesto a disposicion por un servidor
## Que es un Cliente?  
Es un dispositivo que proporciona funciones o servicios a los clientes



- Ejemplo 1:

PC1 -give me .jpg--> PC2

PC1 <---here you are- PC2

1. PC1 Solicita una imagen a PC2 = cliente
2. PC2 Envia la imagen a PC1 = Server

- Ejemplo 2:
> Un dispositivo cliente accede al navegador web donde hace click a un video por lo tanto esta solicitando un video al servidor de youtube.

Internet es una red compleja que es representada con una nube.


PC1 -give me video--> YTSERVER

PC1 <---here you are your video-- YTSERVER


- Ejemplo 3:

> Dos dispositivos Iphone intentan compartir recursos entre si mediante AirDrop.

Iphone1 -give me .jpg--> Iphone 2

Iphone1 <---here you are your .jpg-- Iphone 2


> En conclusion el mismo dispositivo en algunas ocasiones puede ser un cliente y en otras ocasiones un servidor


## Que es un switch?
1. Es un dispositivo que contiene 24 o mas interfaces o puertos que concectan "endhosts" como pc's, servidores
1. Brinda conectividad y Reenvia trafico dentro de una LAN (Local Area Network) pero no en diferentes LAN, ya que se utiliza un dispositivo como el router para esta funcion.
1. Los modelos tipicos de un switch cisco son los catalyst 9200 o 3650.


LAN 1:

PC1-> SW1

## Que es un router?
1. Es un dispostivo que contiene pocas interfaces o puertos 
1. Proporcionan conectividad entre LAN'S
1. Envia datos a traves de internet

LAN2: 

R2 <- INTERNET -> R1 -> SW2 -> PC2

## Que es un Firewall?
1.  Es un dispositivo que monitorea y controla el trafico de la red segun las reglas configuradas para permitirlo o denegarlo.
1. Modelos como ASA 5500X O firepower 2100 estos son conocidos como Firewall de proxima generacion ya que contiene IPS (Sistema prevencion de intrusiones)
1. Protege a hosts internos como pc o servidores Puede ser colocado adentro o fuera de la red.

1. INTERNET - R1 - FW1 - SW1 - PC1
1. INTERNET - FW2 - R2- SW2 - PC2

 


- Que es un firewall basado en host?
1. Son apps basados en software que filtran el trafico que entra y sale de una maquina host



--- 
## LABORATORIO:
- QUE ES LA CLI?
Interfaz linea de comandos que sirve para la configuracion de equipos.


1. Colocar equipos en el area de trabajo
1. Renombrar los equipos
1. Conectar equipos con los otros.