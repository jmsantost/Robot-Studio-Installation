# Robot-Studio-Installation
1. Descarga de Robot Studio
  Para descargar el instalador deben ir a esta página: https://new.abb.com/products/robotics/es/software-y-digital/descargas-de-software y seleccionar el que dice Robot Studio

<img width="1815" height="910" alt="image" src="https://github.com/user-attachments/assets/c7d2ca2f-5017-419b-8f9d-e9fcf442cf3b" />


Deben llenar el siguiente formulario con sus datos y se procederá a descargar
<img width="851" height="1277" alt="image" src="https://github.com/user-attachments/assets/75bf66be-f7e4-4a08-a41c-f19085d245d0" />

2. Mientras se descarga, podemos instalar el VPN necesario para conectarnos al servidor dónde se encuentran las licencias. Para eso debemos ir a vpn.espol.edu.ec. Una vez aquí, ingresar con las credenciales de cada uno.
<img width="1216" height="894" alt="image" src="https://github.com/user-attachments/assets/a38f6591-eafe-4ad4-b638-9ff7675b2ea4" />
Se abrirá la siguiente página y daremos click en Download.
<img width="2504" height="1397" alt="image" src="https://github.com/user-attachments/assets/0d8ba164-4bf9-43d8-a3ae-fdd13d40501a" />
3. Dentro de la carpeta descargada, iremos a Robot Studio y ejecutar Setup

<img width="2559" height="1533" alt="image" src="https://github.com/user-attachments/assets/4e521021-618b-4584-ba03-f61a7b822e20" />
Se escoge el idioma en el que desea el programa
<img width="600" height="233" alt="image" src="https://github.com/user-attachments/assets/7931ee6d-0e09-4f3e-9832-a8b66b3b697c" />
<img width="397" height="296" alt="image" src="https://github.com/user-attachments/assets/e597e0e0-93e3-4293-86d1-0fc4aa2489eb" />
<img width="401" height="302" alt="image" src="https://github.com/user-attachments/assets/a4062ca9-0be7-4048-a5bb-7c800514e664" />
<img width="397" height="300" alt="image" src="https://github.com/user-attachments/assets/a10130ef-d616-4d7d-b63d-2ed043bd582c" />
Escoger la carpeta dónde desea instalar el porgrama
<img width="413" height="302" alt="image" src="https://github.com/user-attachments/assets/5277a317-783c-4a85-a30f-d499b4b96ca7" />
Darle siguiente 
<img width="410" height="308" alt="image" src="https://github.com/user-attachments/assets/8cd2138f-c50b-4f46-a697-be54c7f7607f" />
Darle instalar
<img width="406" height="299" alt="image" src="https://github.com/user-attachments/assets/cc374f72-84d6-4a56-a22a-6522a0c9cfcf" />
Una vez terminada la instalación de Robot Studio, instalaremos la VPN
4. Ejecutamos el archivo descargado para el VPN
<img width="829" height="620" alt="image" src="https://github.com/user-attachments/assets/660edad4-d6f1-48e5-a580-017b066e37c9" />
<img width="811" height="625" alt="image" src="https://github.com/user-attachments/assets/84ab538e-51b0-4d33-9b89-b28c17c3efd7" />
Click en instalar
<img width="804" height="601" alt="image" src="https://github.com/user-attachments/assets/4939d31f-e592-4741-a54d-a37facab43b5" />
Una vez instalado, buscamos CISCO en la barra de buscar de Windows
<img width="1225" height="1172" alt="image" src="https://github.com/user-attachments/assets/575b99b4-adfa-49d6-911b-d0fca942eed4" />
Llenamos con el link del vpn anterior: vnp.espol.edu.ec
<img width="626" height="307" alt="image" src="https://github.com/user-attachments/assets/aa4024a0-9cc3-466a-94c2-d133231a14fb" />
Nos pedirá nuestra cuenta Espol de nuevo
<img width="519" height="346" alt="image" src="https://github.com/user-attachments/assets/be70961b-0794-4930-b1a1-0d30300d749a" />
Para confirmar que estamos conectados a la red Espol, haremos ping aL servidor de las licencias que es 200.126.19.236. Para eso abrimos un cmd y no debería haber perdida de paquetes
<img width="1498" height="903" alt="image" src="https://github.com/user-attachments/assets/ed52bf41-4314-4a41-9241-777259b89e52" />
Con esto, ya estamos seguros que estamos conectados al servidor, abrimos Robot Studio
Al abrirlo nos preguntará que tipo de licencia usaremos, y seleccionamos la de servidor de red
<img width="713" height="501" alt="image" src="https://github.com/user-attachments/assets/12796cb2-a906-4e79-a8cc-1f705e680e2a" />
Llenamos con la IP anterirmente dada
<img width="713" height="501" alt="image" src="https://github.com/user-attachments/assets/0196e356-ca0a-4333-9cb3-58e427bda51f" />
Para comprobar que se tiene la licencia, es necesario ir a Archivo > Opciones
Aqui escoger Licencias y debería salir esto:
<img width="1178" height="853" alt="image" src="https://github.com/user-attachments/assets/3114a1cb-0dd5-43de-a7de-3ddd7d04e084" />
Para poder usar el robot es necesario descargar los controladores y el robot a usar.
Para eso hay que ir a Complementos y a la primera pestaña RobotWare, click en RobotWare para IRC5, a la izquierda se abrirá una pantalla en la que hay que seleccionar la versión 6.11.01 y click en Añadir. Esto tomará unos 5 minutos y en la parte inferior derecha verá la barra de progreso.

<img width="2559" height="1532" alt="image" src="https://github.com/user-attachments/assets/6b58c872-e845-471c-9484-570bd1ed33e8" />

Ahora es necesario descargar el robot. Para esto, Click enla pestaña Modelo de RobotStudio y seleccionar IRB 2600
Hay que tener en cuenta que el Modelo del robot: IRB 2600 12 kg 1.65 m (versión estandar, no tipo C)
<img width="2559" height="1521" alt="image" src="https://github.com/user-attachments/assets/ad855e64-d9ad-4f0f-8bed-6ca96bba5ce1" />
Una vez instalado esto, el programa pedirá reiniarse. 
Para empezar a trabajar hay que dar click en Archivo >Nuevo y tener en cuenta esto 
Distribución del RobotWare: 6.11.01
Modelo del robot: IRB 2600 12 kg 1.65 m (versión estandar, no tipo C)
<img width="2559" height="1514" alt="image" src="https://github.com/user-attachments/assets/f4dcdcb1-db13-41dd-bffe-f3beb6e03c04" />

Con esto ya podrán hacer uso de RobotStudio
