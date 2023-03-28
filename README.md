# Cuestionario previo laboratorio 3
## 1.Investigue sobre la especificación de la interfaz SPI. Preste atención a los aspectos necesarios para poder diseñar un controlador maestro de SPI, además de los diferentes modos de SPI


 La interfaz SPI, Serial Peripherical Interface, consiste en un estándar de comunicación síncrono entre un dispositivo denominado como maestro y otros denominados esclavos.
 El dispositivo maestro controla la comunicación con los esclavos, permitiéndole enviar o recibir información, utilizando las líneas MOSI(Master Out, Slave In) y MISO (Master In, Slave Out) y Chip Select. Además, se utiliza una señal de reloj para sincronizar los datos.
 
 Existen dos formas principales de realizar las conexiones entre los dispositivos en un sistema SPI. En el modo directo se cuentan con las 4 línea anteriormente mencionada, estando todos los esclavos conectados en paralelo a las líneas de reloj,MOSI y MISO, mientras cada uno cuenta con un Chip Select individual. También existe el modo conocido como Daisy Chain, donde los dispositivos esclavos se conectan en cascada, compartiendo las líneas de reloj y Chip Select.
 
 
 
 ![SPI](https://user-images.githubusercontent.com/99456315/228150246-fd4b7c5e-8697-47f4-a37a-e0d74db4d4f4.jpg)

Diagramas de los dos tipos principales de conexión SPI [1]

El tipo de conexión dependerá de la capacidad del dispositivo maestro para generar distintas señales individuales de Chip Select.

## 2.Investigue sobre la comunicación serie UART. Preste atención a las diferentes características de configuración necesarias para la comunicación serie mediante UART (por ejemplo, baud rate, paridad, etc). Además, investigue cómo puede utilizar puertos serie en su computadora, considerando el sistema operativo que utilice.

El protocolo de comunicación serie UART (Universal Asynchronous Receiver/Transmitter), utiliza dos líneas, recepción y transmisión para comunicar dos dispositivos.
Entre las principales características de este protocolo se encuentran:

* Comunicación asíncrona y bidireccional.

*Ambos dispositivos deben configurarse para que trabajen a la misma cantidad de baudios, normalmente entre 300 y 1150k.

* La trama de bits se conforma por un bit de inicio, de 5 a 9 bits de información, un bit de paridad y un bit de finalización. El bit de pardidad indica si el canal modificó la información durante la transmisión


![UART](https://user-images.githubusercontent.com/99456315/228155548-c59963b4-e956-44c7-9187-098c8393c80f.jpg)

Diagrama de conexión de dispositivos UART [3]

En las computadoras suelen utilizarse puertos de comunicación serie como USB, RS-232,SATA,PCIe... Para conectar periféricos como teclados, mouse, monitor... Para configurar la conexión de dispositivos que utilicen comunicación serial se suele utilizar la terminal, aunque tambipen existe software como Putty que se puede utilziar tanto en Windows como en Múltiples sistemas Unix.

Referencias
[1] Pini A. 2019. Por qué y cómo usar la interfaz periférica serial para simplifi-
car las conexiones entre distintos dispositivos. Access on : march,27,2023.Available:
https://www.digikey.com/es/articles/why-how-to-use-serial-peripheral-interface-simplify-
connections-between-multiple-devices

[2] Dhaker P. S.F. Introduction to SPI Interface. Access on : march,27,2023.Available:
https://www.analog.com/en/analog-dialogue/articles/introduction-to-spi-interface.html

[3] Peña E., Legaspi M. N.A.UART: A Hardware Communication Protocol Understanding Universal Asynchronous Receiver/Transmitter. Access on: march,27,2023.Available:
https://www.analog.com/en/analog-dialogue/articles/uart-a-hardware-communication-protocol.html

[4] Chipkin. N.A. Using PuTTY for serial COM connections (HyperTerminal replacement). Access on: march,27,2023. Available on: https://store.chipkin.com/articles/using-putty-for-serial-com-connections-hyperterminal-replacement
