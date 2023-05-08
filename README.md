# Porpuesta de diseño Laboratorio 4
## 4.2 Microcontrolador RISC V

Para el desarrollo del microcontroaldor, se tomará como base el diseño de un procesador uniciclo presentado en el libro Digital Design and Computer Architecture RISC V Edition:



![Diseño_lab4_1s2023](https://user-images.githubusercontent.com/99456315/236791063-e1140dd6-b4d0-4a44-b722-7aec50a2edf7.jpg)

Esquemático de un procesador uniciclo. [1]

Donde se tienen los siguientes módulos:
* Program Counter: Módulo encargado de controlar la ejecución de las instrucciones, conteniendo el valor de la dirección en memoria de la instrucción a ejecutar.
* Sumadores: Estos se encargan de incrementar el valor del Program Counter, según las instrucciones.
* Memoria de datos: Aquí se almacenan los valores de los periféricos como LEDS, 7 Segmentos y switches, así como los registros de control y de datos de cada puerto de comunicación UART.
* Memoria de Instrucciones: Aquí se almacenan las instrucciones a ejecutar por el programa en ensamblador RISC-V encargado de controlar el micrcontrolador.
* Register File: Es un banco de registros que se utilizan para almacenar datos de memoria a utilizar en las distintas operaciones, así como almacenar los resultados de las mismas antes de pasar a memoria.
*  ALU: Unidad aritmético-lógica, encargada de realizar operaciones como suma, resta,and, or, logical shift...
* Multiplexores: Encargados de seleccionar entre dos posibles datos, según las unidades de control.
* Unidad de Control: 
* Unidad de Control de la ALU:
## 4.3  Periféricos
## 4.4 y 4.5 Aplicación y programa de ensamblador

Con base en la descripción del funcionamiento del sistema se desarrolló el siguiente diagrama de estados:


![Diseño_lab4_1s2023](https://user-images.githubusercontent.com/99456315/236823336-60bf974e-d228-4f38-87a9-b59ff23a7386.jpg)

Diagrama de Estados del funcionamiento del Microcontrolador

## Referencias Bibliográficas
1.  Harris & Harris
 
