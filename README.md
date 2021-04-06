
# UNIVERSIDAD DE LAS FUERZAS ARMADAS-ESPE
 
![](https://upload.wikimedia.org/wikipedia/commons/3/3a/Logo_ESPEOk.png)


---------------------
#  LABORATORIO 8
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                           
                                                                           
       Janeth Katherine Oyasa Sepa, Juan Daniel Tixi Yupa
       DEPARTAMENTO DE ELECTRICA Y ELECTRONICA
       ESPE, Autopista General Rumiñahui S/N y Ambato, Sangolquí 171103.
       E-mail: jkoyasa@espe.edu.ec, jdtixi@espe.edu.ec
       Noviembre 2020 – Abril 2021
       Fundamentos de Circuitos Eléctricos
       
       
       
       
_____________________________________________________________________________________      
# 1. Objetivo General

Desarrollar mediante la teoría y práctica, el principio de funcionamiento de un Amplificador Operacional de circuitos eléctricos, además, de comparar los resultados calculador con los datos resultantes del simulador. 

_____________________________________________________________________________________      
# 2. Objetivos Específicos 

-	Distinguir cada una de las características de un Amplificador Operacional.
-	Analizar la relevancia de un Amplificador Operacional en circuitos eléctricos.
-	Identificar la particularidad de las entradas y la salida del dispositivo. 

_____________________________________________________________________________________      
# 3. Marco Teórico 

Al llegar al desarrollo de los últimos temas del syllabus de este semestre, tenemos un conocimiento más amplio de conceptos básicos de modo que podemos empezar el análisis de temas más complejos como es el caso de este último laboratorio donde se analizara de manera practica y teórica el Amplificador Operacional en circuitos eléctricos. Además, es importante comprender el funcionamiento del Amplificador Operacional como de sus señales mediante las capturas realizadas a lo largo del procedimiento, tomando como ejemplo del circuito descrito en la guía N°9, a partir, del mismo se desarrollará el análisis matemático e ilustrativo para que este nuevo tema se pueda comprender en su totalidad.  

Es importante que antes de continuar con la práctica en el simulador se pueda analizar y determinar la relación entre las señales de entrada y salida en cada uno de los circuitos que se indican en  la guía, lo cual implica reducir el tiempo de realización del proceso, incluso disminuir los recursos usados para el hallazgo de los resultados expuestos en el apartado de cálculos, también es importante demostrar simultáneamente las señales de entrada y salida en un osciloscopio, capturando las formas de onda para formular el análisis concluyente de las medidas tomadas con el simulador mejorando la comprensión del mismo. 


### *** Amplificador Operacional  ***

El surgimiento del Amplificador Operacional también conocido como Op-Amp, debido a sus siglas en inglés (Operational Amplifier) data alrededor del año 1964, de manos del ingeniero electrónico estadounidense Robert John Widlar, quien también es un diseñador de circuitos integrados lineales (CI). Podemos nombrar al amplificador operacional como un dispositivo de alta ganancia acoplado en corriente continua que mantiene dos entradas y una salida, tal como mencionamos anteriormente, así, sabemos que generalmente la salida del dispositivo como tal es mil veces mayor a la diferencia de potencia entre las entradas. 

Además, sabemos que tiene una entrada positiva y una negativa, por lo que, si la entrada positiva es superior en voltaje a la entrada negativa, la salida tiene a irse al voltaje de saturación. Un Amplificador Operacional puede esta alimentado por fuentes diferentes es decir uno de voltaje negativo y uno positivo o mediante fuentes simples como voltaje positivo y GND. Incluso es conveniente recordar que un Amplificador Operacional contiene diversas configuraciones, tal es el caso de: amplificador, no inversor, inversor y sumador. 

(PRIMERA IMAGEN)

En otras palabras, también podemos decir que los amplificadores operacionales son conocidos como dispositivos lineales de alta ganancia compactos activos ocupados para suministrar la función de transferencia deseada. En el caso de los amplificadores operacionales (A.O.) se componen de un circuito electrónico con una salida, que se obtienen mediante la diferencia de las dos entradas que tiene multiplicadas por el factor de ganancia en teoría la formula seria: 

                                                 G .(V+ -V-)

Una de las características de un Amplificador Operacional se expresa debido a su preparación en componente más genéricos, mostrado de modo que se puede acceder a los puntos digitales vitales donde se pueden interconectar los componentes externos que permiten al usuario cambiar la respuesta y transferencia del dispositivo. 


### *** Etapas de los Amplificadores Operacionales ***


(SEGUNDA IMAGEN)

Entonces de aquí recalcamos dos configuraciones del Amplificador Operacional importantes: Lazo Abierto y Lazo Cerrado.


### *** Configuración del Amplificador Operacional en lazo abierto ***

(TERCERA IMAGEN)

Para entender mejor la ganancia del amplificador en lazo abierto debemos tomar en cuenta esta fórmula: 

                                                                             Av = Vs / Ve

También se debe tomar en cuenta que, al aplicar una señal de entrada en nuestro circuito eléctrico, entonces se considera como ganancia el cociente entre la tensión de la salida (Vs) y la entrada (Ve) que mantiene el amplificador operacional cuando no existe ningún lazo de realimentación entre las dos entradas y la salida. Además, es fundamental entender que el amplificador operacional ideal, mantiene ganancia infinita. Sabiendo que este tipo de configuración se utiliza en comparadores, donde deseamos saber cuál de las entradas contienen mayor tensión. Incluso conocemos que la ganancia en lazo abierto es la salida máxima que se puede obtener del amplificador operacional.


### *** Configuración del Amplificador Operacional en lazo abierto ***

(CUARTA IMAGEN)

Para entender la configuración del amplificador operacional en lazo cerrado decimos que mediante su uso se reduce notablemente la ganancia del dispositivo porque estaba determinada por la red de realimentación y no por las características que mantiene el dispositivo en cuestión. 

La ganancia se obtiene mediante la siguiente fórmula:  
                                                                              Av = - Vo/Vin
                                                                                       
Sabiendo que el signo negativo indica que la señal en la salida va ha ser opuesta a la que se encuentra en la entrada, entonces decimos que se comprueba que la señal positiva que se aplica a una entrada genera una tensión negativa en la salida y viceversa. 


_____________________________________________________________________________________     
# 4. Lista de componentes

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/168898803_279351633630880_1263561550144821975_n.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_ohc=5U1QO4ifvMUAX-ItNhD&_nc_ht=scontent.fuio1-1.fna&oh=77fee0d204c8445d4a5f0afab8205870&oe=609020CC)


_____________________________________________________________________________________     
# 5. Explicación

En esta práctica nos centramos en el armado de circuitos con amplificadores operacionales, los cuales se diseñan de tal forma que, la llamada resistencia de feedback sea mayor que la resistencia o las resistencias de estradas, caso contrario tendríamos un atenuador. 

Siempre es bueno saber cómo se deben colocar los elementos en la Protoboard, por los que se incluye su armado respectivo.

Amplificador inversor

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169266249_3785178101578691_3235456498124425969_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_ohc=OXjqDA-uAEIAX8wPoU8&_nc_ht=scontent.fuio1-1.fna&oh=350bd5377d7c56d67c3db902529a3b78&oe=6091AC93)

Amplificador Integrador

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169555483_3785178091578692_8294201664013953603_n.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_ohc=yvOA-7PZVo4AX-eMMgd&_nc_ht=scontent.fuio1-1.fna&oh=c8dfc63010c2a3076df83841c3ca1c7c&oe=6092323B)

Amplificador Sumador

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/170065576_3785184761578025_662369522717463612_n.jpg?_nc_cat=109&ccb=1-3&_nc_sid=730e14&_nc_ohc=xFdgGgOT1VgAX-mibvN&_nc_ht=scontent.fuio1-1.fna&oh=990959167c259b19d866670bb7cd978f&oe=60936653)


**El primer circuito **que se arma en esta práctica es un amplificador inversor, el cual está dispuesto de tal forma que aumenta la amplitud de la onda de entrada y la invierte.

La ganancia del circuito se encuentra de la siguiente forma:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/168867561_279351646964212_3722550719847094383_n.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_ohc=Mxh3rd8ec_QAX-UbSWW&_nc_ht=scontent.fuio1-1.fna&oh=36ebeb0a4c347d2ade3c94cca34d46e7&oe=60910F6F)

Donde Vs es el voltaje de salida, Ve es el voltaje de entrada, Rf es la resistencia de feedback y R1 es la resistencia de entrada.

Para el primer circuito tenemos el voltaje de salida así:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/168470247_279351630297547_393647535357954435_n.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_ohc=fXOD5ahqnTcAX-tbEau&_nc_ht=scontent.fuio1-1.fna&oh=2d9e387c1c86f1aabfc5e2a9e91a81ca&oe=608EBF4A)

Al medir en el osciloscopio nos sale:

v_s=4.35 V

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169901904_3785194178243750_6967272421793020997_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_ohc=TigTUayd84MAX8k-eMv&_nc_ht=scontent.fuio1-1.fna&oh=80a6479c4a716169bf19d7683986425d&oe=60905442)


![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/168858472_279351673630876_6331085106977493206_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_ohc=NMyHOJ695d4AX8UySMO&_nc_ht=scontent.fuio1-1.fna&oh=64a908e6adddae8b34d0390647cf1957&oe=6090B1A5)

Este es el circuito armado en LTspice

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169071116_279351710297539_36590157758807616_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_ohc=bPZd0T-Qcy4AX_kE6HA&_nc_ht=scontent.fuio1-1.fna&oh=0b4f1217c20819372fe9caae65901ced&oe=608F1C06)

Esta imagen nos provee de la señal de entrada y salida del OpAmp, claramente observamos que son las formas de onda esperadas, la onda de la señal de entrada es menor en amplitud que la de salida, además que la onda de salida esta invertida ya que estamos usando un amplificador inversor.


**El segundo circuido ** es conocido como un 
amplificador integrador

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/168829328_279351716964205_717026854129172407_n.jpg?_nc_cat=104&ccb=1-3&_nc_sid=730e14&_nc_ohc=6PCJA_JT3igAX89Bfhm&_nc_ht=scontent.fuio1-1.fna&oh=af73192afa05ddf2c1d775f35fd388d8&oe=6091786F)

Cuyo voltaje de salida se lo calcula de la siguiente forma:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169935602_3785199481576553_4272227557910600068_n.jpg?_nc_cat=103&ccb=1-3&_nc_sid=730e14&_nc_ohc=eCalV2OsHwcAX8TlwR8&_nc_ht=scontent.fuio1-1.fna&oh=d4dd29ab43861b80e5445134ffafcb45&oe=60926943)


![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169156041_279351653630878_1872806786958430582_n.jpg?_nc_cat=104&ccb=1-3&_nc_sid=730e14&_nc_ohc=NZ23aTgREQsAX93NjRL&_nc_ht=scontent.fuio1-1.fna&oh=b1323f02ba2cd775dfa3a365da4af885&oe=608DE9EA)

Comparando las señales de entrada y salida, nos damos cuenta de algo nuevo en este circuito, como tenemos una entrada en forma de señal de onda, lo que hace este circuito es integrar la señal, con lo cual tendríamos una salida con una señal triangular, esto se produce debido a las propiedades de los capacitores.

El tercer circuito es un amplificador sumador, se le llama así porque el voltaje de salida es la suma de los voltajes de salida de las dos entradas.

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169256863_279351726964204_6577480761288332558_n.jpg?_nc_cat=106&ccb=1-3&_nc_sid=730e14&_nc_ohc=PUt2OEmh3k0AX-aOu-R&_nc_ht=scontent.fuio1-1.fna&oh=ab26c5d5faedc8760559bec584c7e644&oe=608E12C7)

Y su voltaje de salida se lo deduce sabiendo que la corriente que pasa por la resistencia de 1k Ohm es la suma de las corrientes que pasan por las resistencias de 300 y 200 Ohm, por tanto:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169141263_279351763630867_3498314226092977300_n.jpg?_nc_cat=109&ccb=1-3&_nc_sid=730e14&_nc_ohc=jsLAZ9kjYokAX9PxWtn&_nc_ht=scontent.fuio1-1.fna&oh=74de86678aa4758eac2729728ac79976&oe=608E01C8)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/169901904_3785178031578698_5048849120406373789_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_ohc=RK62xXOGz9YAX8O475C&_nc_ht=scontent.fuio1-1.fna&oh=faa01a68a5417d3764efeb7f460a566d&oe=60917684)


Y así tenemos a relación entre el voltaje de salida y entrada, que es la ganancia para este circuito.

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/168535538_279351663630877_7246233740241783472_n.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_ohc=GwsuschYJPQAX8uAvVg&_nc_ht=scontent.fuio1-1.fna&oh=9df739062bd26b16da59e335ff805d03&oe=6090985C)

En la imagen, podemos observar las ondas de salida y de entrada del OpAmp, en el que la señal de entrada esta es mucho menor que el de salida y la salida igualmente esta invertida y tiene su pico o valor más alto en el voltaje de ganancia del OpAmp.


En común todos están adaptados para que la señal de entrada se amplíe y se invierta y que no se saturen con los voltajes de alimentación positivos y negativos.

### Preguntas

Anote parámetros técnicos importantes de un amplificador operacional que deben será tomados en cuenta al momento de utilizarlos en un proyecto.

Cada elemento de un circuito eléctrico viene acompañado de si hoja técnica o datasheet, en el que encontramos todos los datos técnicos del elemento que vamos a usar, en este caso del OpAmp LM 741 tenemos:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/168646297_279351783630865_1109282545536701738_n.jpg?_nc_cat=104&ccb=1-3&_nc_sid=730e14&_nc_ohc=FYIuL2wrQuEAX8NI_Nd&_nc_ht=scontent.fuio1-1.fna&oh=9fba2b8bef1ccc016b7c36da36838e22&oe=60900F4A)

En esta tabla de datos encontramos datos importantes como el valor de la resistencia de entrada, los voltajes offset, los cuales en un OpAmp debe acercarse a 0.

Además de los valores de la resistencia de salida, que en este caso es 75 Ohm, que en un OpAmp ideal debería ser cero.



_____________________________________________________________________________________     

# 8. Conclusiones  

_____________________________________________________________________________________     

# 9. Bibliografía 
       
       
