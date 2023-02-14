# Cuestionario Previo

## Pregunta 1:

**Investigue las características de las familias TTL bajo las series 74∗xx en particular las diferencias entre las variantes ∗ ∈ {L, LS y HC}.**

 Es una familia de circuitos integrados transistor-transistor lógicos, el cual por su bajo costo gano mucha popularidad en el mercado y en el grado militar. Estos al paso de los anos dieron el paso a incluir el soporte de  tecnología CMOS de bajo consumo. En tiempos más actuales, son usados comúnmente por su facilidad de montar en una breadboard, lo cual lo vuelve un excelente candidato para estudiantes. La serie 7400 contiene cientos de compuertas lógicas básicas, flip-flops y hasta ALU.
La principal diferencia entre los 74L y 74LS es que el Low-power shotcky, es el más bajo consumo y velocidades más rápidas y que el 74L es una tecnología obsoleta, sin embargo, el 74HC es un CMOS de más velocidad y menor consumo, aparte de ser más nuevo.



## Pregunta 2:

**Investigue las características de la familia CMOS 4000.**
 
La familia CMOS 4000 tiene un supply de 3 a 15V, donde sus entradas son de alta impedancia.
Tiene un output pequeño de alrededor de 1mA, esto para mantener un outup de voltaje correcto para manejar el input, pero si esto no necesario, su máximo es de 5mA con un suministro de 6V o 10mA a 9V. Posee Fan-out de hasta 50 inputs y un tiempo de propagación en el gate de 30ns con una entrada de 9V. Su frecuencia va hasta 1MHz y su consumo en baja frecuencias esta en los µW, mientras que a altas frecuencias se ubica en los mW.

## Pregunta 3:

**Investigue que cuidados deben tenerse al manipular las tecnologías CMOS**

Al manipular estos dispositivos tenemos que tener en cuenta: protección electroestática (ESD protection), si vamos a manejar estos dispositivos que el suministro este apagado para prevenir danos por pico eléctricos o cortos, que los dispositivos estén limpios ya que son susceptibles a la contaminación, esto va de mano con un buen manejo al empacarlos y guardarlos, que sea en lugares no húmedos, tener cuidado con los pines ya que esto puede dañarlo por completo y cuidar la exposición al calor, ya que esto puede reducir la vida útil del dispositivo.

## Pregunta 4: 

**Investigue el significado de los parámetros VIL, VIH, VOL, VOH, IIK, IOK**

> **VIL:** Low-Level Input voltage, es el mínimo voltaje que una entrada digital puede tener para ser reconocida como un Bajo/Low/Cero

> **VIH:** High-Level Input Voltage, es el máximo voltaje que una entrada digital puede tener para ser reconocida como un Alto/High/Uno

> **VOL:** Low-Level Output voltage, es el mínimo voltaje que una salida digital puede tener para ser reconocida como un Bajo/Low/Cero

> **VOH:** High-Level Output Voltage, es el máximo voltaje que una salida digital puede tener para ser reconocida como un Alto/High/Uno

> **IIK e IOK:** No aparece información en la literatura o en el internet acerca de IOK o el IIK. Sin embargo, podemos tomarlos como, IIL (Low-Level Input Current) y IIH (High-Level Input Current) son el mínimo y el máximo de corriente, respectivamente, que una entrada digital puede tener para ser reconocida como un Bajo/Low/Cero y Alto/High/Uno. También, IOL (Low-Level Output Current) y IOH (High-Level Output Current) son el mínimo y el máximo de corriente, respectivamente, que una salida digital puede tener para ser reconocida como un Bajo/Low/Cero y Alto/High/Uno.

## Pregunta 5: 

**Investigue qué son los tiempos de propagación tPD, tPLH y tPHL y los tiempos de transición tt , tr y tf .**

-	El tiempo de propagación que se puede abreviar como tPD se refiere al tiempo que tarda una señal en viajar a través de un medio de transmisión, como un cable o una guía de ondas, de un punto a otro. El valor exacto de tPD depende de las propiedades del medio.

-	 El retardo de propagación de apagado de bajo a alto (TPLH) y retardo de propagación de apagado de alto a bajo (TPHL) se refieren al tiempo que tarda una señal en pasar de un estado bajo a un estado alto y viceversa. Estos tiempos son importantes para determinar el rendimiento de los circuitos digitales, ya que pueden afectar la velocidad y la precisión de las señales que se transmiten.

+ 	El tiempo de transición se utiliza para describir el tiempo que tarda una señal en pasar de un nivel de voltaje a otro. Hay tres definiciones de uso común de tiempo de transición en la electrónica digital:

+	Tiempo de transición total (tt): El tiempo de transición total es el tiempo que tarda el nivel de voltaje de una señal en pasar de un nivel de voltaje a otro. Esto a menudo se define como la suma del tiempo de subida y el tiempo de caída y se usa para describir la tasa general de cambio de una señal.

+	Tiempo de subida (tr): El tiempo de subida es el tiempo que tarda el nivel de tensión de una señal en pasar del 10 % al 90 % de su valor final. Esto se usa a menudo para describir la tasa de cambio de una señal y es un factor clave para determinar el ancho de banda de un circuito digital.

+	Tiempo de caída (tf): El tiempo de caída es el tiempo que tarda el nivel de voltaje de una señal en pasar del 90 % al 10 % de su valor final. Al igual que el tiempo de subida, el tiempo de caída se utiliza para describir la tasa de cambio de una señal y es un factor clave para determinar el ancho de banda de un circuito digital.


## Pregunta 6:

**Investigue qué significa el término fan-out y cuales valores típicos se encuentran en las familias TTL y CMOS.**

Fan-out se refiere al número máximo de cargas que una salida digital puede manejar sin afectar el nivel de voltaje 
de la señal de salida. Es una medida de la fuerza de la unidad de salida de un dispositivo digital y es un parámetro importante en el diseño de circuitos digitales. El fan-out se especifica en términos de la cantidad máxima de cargas equivalentes que puede manejar una salida digital. Una carga equivalente se define como una carga con una impedancia y capacitancia específicas que representa una carga estándar que puede ser impulsada por la salida. En términos prácticos, el fan-out es importante en el diseño de circuitos digitales porque determina cuántas cargas puede manejar una salida digital sin afectar el nivel de voltaje de la señal de salida
Los valores típicos de fan-out en circuitos digitales TTL (Transistor-Transistor Logic) y CMOS (Complementary Metal-Oxide-Semiconductor) pueden variar ampliamente según el dispositivo específico y las condiciones de funcionamiento. Sin embargo, las siguientes son pautas generales para el fan-out en estos dos tipos de circuitos digitales:

> **TTL:** la distribución de los dispositivos TTL suele ser de 10 a 20 cargas. Esto significa que una salida TTL puede controlar de 10 a 20 entradas TTL más sin afectar el nivel de voltaje de la señal de salida. 

> **CMOS:**  la distribución de los dispositivos CMOS suele ser mucho mayor que la de los dispositivos TTL, con valores que van de 50 a 100 o más. Esto se debe al bajo consumo de energía y la alta impedancia de entrada de los dispositivos CMOS, que les permiten manejar muchas más cargas sin afectar el nivel de voltaje de la señal de salida. Los dispositivos CMOS se utilizan ampliamente en circuitos digitales que requieren un bajo consumo de energía y una gran distribución, como los microprocesadores y los circuitos de memoria.


## Pregunta 7:

**Para cada una de las variantes TTL y CMOS especifique en una tabla: a) rango de tensión eléctrica de alimentación VCC o VDD, VSS b) rango de tensiones de entrada y salida c) tiempos de propagación y transición **



|TTL |CMOS|
|----|----|
|VCC o VDD|5 V|3-18 V|
|VSS|0 V|0 V|
|Tiempo de propagación (tPD)|En el rango de varios nanosegundos a decenas de nanosegundos| En el rango de varias decenas de nanosegundos a varias centenas de nanosegundos|
|Tiempo de transición (tt)| En el rango de varios nanosegundos a decenas de nanosegundos |En el rango de varias decenas de nanosegundos a varias centenas de nanosegundos|


## Pregunta 8:

**Revise la hoja de datos de los circuitos integrados 74∗00,74∗02,74∗04,74∗14, 4001, 4011, 4069 y 40106. Resuma para qué sirve cada uno.**

	1. **74x00:** La serie 74x00 es una familia de compuertas NAND cuádruples de dos entradas. Proporciona cuatro puertas NAND independientes de dos entradas en un solo paquete.
	2. **74x02:** La serie 74x02 es una familia de compuertas NOR cuádruples de dos entradas. Proporciona cuatro puertas NOR independientes de dos entradas en un solo paquete.
	3. **74x04:** La serie 74x04 es una familia de inversores hexagonales. Proporciona seis inversores independientes en un solo paquete.
	4. **74x14:** La serie 74x14 es una familia de inversores hexagonales Schmitt-Trigger. Proporciona seis inversores Schmitt-Trigger independientes en un solo paquete.
	5. **4001:** El 4001 es una puerta NOR cuádruple de dos entradas. Proporciona cuatro puertas NOR independientes de dos entradas en un solo paquete.
	6. **4011:** El 4011 es una puerta NAND cuádruple de dos entradas. Proporciona cuatro puertas NAND independientes de dos entradas en un solo paquete.
	7. **4069:** El 4069 es un búfer de inversión hexadecimal. Proporciona seis amortiguadores de inversión independientes en un solo paquete.
	8. **40106:** El 40106 es un inversor Schmitt-Trigger hexagonal. Proporciona seis inversores Schmitt-Trigger independientes en un solo paquete.
	

## Pregunta 9: 

**Revise la estructura básica, a nivel de transistores, de una compuerta NAND en circuitos integrados CMOS**


Una compuerta NAND se caracteriza por ser la negación de la compuerta AND; es decir, que cuando el comportamiento AND da como resultado un 1, el NAND lo transforma a un 0.Esto se debe cumplir para la misma combinación de entradas en ambas compuertas. 
Cabe resaltar que la salida en alto para la compuerta AND se da solo cuando todas sus entradas 
se encuentran en alto, por lo que el NAND dará una salida en 0 para este mismo caso. Lo que 
conlleva a tener salidas en 1 solo cuando existe valores en bajo desde la entrada.

Harris & Harris pag 19
	
En cuanto a la tecnología CMOS y las compuertas NAND, su estructura para dos entradas 
se caracteriza por componerse de dos transistores tipo N y dos tipo P. La configuración entre
los transistores N se establece en serie; por lo que en los tipo P se conectan en paralelo. Lo que permite que los Pull-Down de los transistores N se activen y los Pull-Up de los P se anulen, solo cuando se tiene entradas con valores en 1.
	
	
	Pegar fotos de la fig 1.33 pag 54 pdf harris & harris
	
	
## Pregunta 10: 

**Investigue sobre el concepto y el uso de los de circuitos pull-up y pull-down en electrónica digital.**

Las compuertas lógicas se caracterizan por ser dispositivos que necesitan señales constantes, ya que tienen áreas de trabajo. Lo que provoca que cada tecnología sea sensible a cambios en las señales. Se conoce que cada compuerta lógica se desarrolla con configuraciones de transistores, lo que implica que cada uno de estos transistores debe trabajar en sus zonas correctas y así interpretar correctamente la entrada para suposterior salida.
	
Es aquí donde los circuitos pull-up y pull-down entran en la escena. Pues son estos, los que
se encargan de establecer y censar en que valor establecer la señal. Para el caso del circuito pull-up, el comportamiento es recibir una entrada en 1 y ser capaz activarse para que la tensión se centre en la resistencia y pueda mostrar un 0 lógico en su salida.
De lo contrario, su entrada es 0 con una salida lógica en alto.
imagen de 
	
El circuito Pull-down por su parte, mantiene su entrada cercana a el valor de 0. Lo que permite un valor de 1 cuando el switch se cierra. Pues lo aproxima al valor de Vin.

	imagen de https://www.circuitbasics.com/pull-up-and-pull-down-resistors/
	
	
	
Ambas configuraciones permiten que dispositivos como Arduinos o FPGAs sean capaces de comunicarse con periféricos, y de una forma estable entre valores constantes de señales en alto o bajo.
	
	
		
## Pregunta 11:

**Investigue qué es un circuito disparador Schmitt (Schmitt trigger). Revise las características técnicas del circuito 74*14**


El Circuito Disparador Schmitt consiste en un circuito de entrada lógica; el cual proporciona dos diferentes niveles de voltajes umbral, tanto para las secciones de alto y bajo.Lo que genera una señal con dichos niveles definidos y poco afectada por ruido.
	
Para las características técnicas del circuito 74x14, se toma como referencia la compuerta inversora 74HC14. Esta utiliza el circuito de Schmitt para entablar los niveles y que las señales no se intervcalen entre los niveles lógicos TTL del dispositivo. Además de eliminar la adhesión de ruido a la misma señal tratada. 
	
	
	https://c1555f5ec9.clvaw-cdnwnd.com/34662fcf1f1e607c561442431023ac8e/200006185-95b2196ab9/74HC14%20Datasheet.pdf
	
	
## Pregunta 12: 

**Investigue qué es el efecto de rebote y típicos circuitos anti-rebote (debouncing circuits)**
	
El efecto rebote se debe a que en la práctica y con elementos físicos, no es posible obtener un voltaje limpio  desde un interruptor; pues consiste en la acción de movimiento desde una posición a otra. Donde el voltaje se transfiere de manera intermitente hasta que se establezca en la posición selecciona. Aunque su duración no es perceptible, existen aplicaciones donde ese tiempo es lo suficiente para un mal funcionamiento.
	
Para lograr el mejor rendimiento de cualquier interruptor y no verse afectado por el rebote de los circuitos;existen los circuitos anti-rebote y se ven manifestados por un comportamiento con memoria. Un ejemplo de estos son los latch o flip-flops, pues son capaces de tener un valor en salida durante el tiempo de variación de su entrada, hasta que se estabilice.libro sistemas digitales pag pdf 242-243

## Pregunta 13:

**Explique qué es el modelado de comportamiento y de estructura en diseño digital. Brinde un ejemplo de cada uno. Explique qué es el modelado de comportamiento y de estructura en diseño digital. Brinde un ejemplo de cada uno.**

El modelado estructural consiste en describir un módulo utilizando los componentes básicos como compuertas lógicas. Por ejemplo, diseñar un “Half-adder” utilizando una compuerta XOR y una AND.

El modelado por comportamiento se refiere a describir un módulo basándose en su comportamiento, como con una tabla de verdad, y utilizando estructuras como if o case. Por ejemplo, modelar un multiplexor basado en su comportamiento, sin considerar las compuertas necesarias para desarrollarlo.

## Pregunta 14.

**Explique el proceso de síntesis lógica en el diseño de circuitos digitales, tanto para el desarrollo de un ASIC como para una FPGA.**

La síntesis lógica consiste en el proceso de tomar un diseño en alto nivel e implementarlo a bajo nivel, con elementos fundamentales. Por ejemplo, Vivado transforma el diseño en alto nivel (SystemVerilog) en un diseño RTL, el cual es implementado en una FPGA o ASIC.

## Pregunta 15:

**Investigue sobre la tecnología de FPGAs. Describa el funcionamiento de la lógica programable en general, así como los componentes básicos de una.**

Una FPGA consiste que permite implementar diseños de circuitos digitales descritos en un leguaje de descripción de Hardware, conocidos como HDL. Entre los componentes básicos de una FPGA se encuentran los puertos de entrada y de salida, RAM, relojes, registros, PCI, bloques lógicos combinacionales…

# Referencias
harris / harrris
http://www.elecdude.com/2014/07/differences-in-cmos-4000-series-74ls-74hc-74hct.html
https://www.circuitbasics.com/pull-up-and-pull-down-resistors/
https://c1555f5ec9.clvaw-cdnwnd.com/34662fcf1f1e607c561442431023ac8e/200006185-95b2196ab9/74HC14%20Datasheet.pdf
