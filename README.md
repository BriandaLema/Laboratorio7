# LABORATORIO # 07

TEMA: CARACTERÍSTICAS DE LA ONDA SENOIDAL
## 1. OBJETIVOS

**1,1.- GENERAL** 

* Analizar experimentalmente las características de señales senoidales.

**1,2.-ESPECÍFICOS**

* Comprobar un circuito de corriente alterna con señal senoidal.

* Verificar la manera de medir el voltaje, periodo y frecuencia en señales senoidales

## 2. PLANTEAMIENTO DEL PROBLEMA

Este proyecto consistió en la implementación de un circuito  lineal, en un programa online denominado Tinkercad con la finalidad de analizae las características de las señales senoidales. Se crea el circuito utilizando resistencias en serie conectadas a un generador de funciones, la cuál es la característica principal para poder utilizar un osciloscopi y poder visualizar el osciloscopio.


## 3. MARCO TEÓRICO 

**CORRIENTE ALTERNA Y ONDAS SENOIDALES**

La corriente alterna AC es aquella que varía su magnitud en función del tiempo. Las ondas senoidales son patrones de ondas que representan matemáticamente las funciones seno y coseno. Estas ondas representan el valor de la tensión o corriente a través de la variación del tiempo, en 2 ejes cartesianos denotados en amplitud y tiempo.

**CARACTERÍSTICAS DE LAS ONDAS SENOIDALES**

* **AMPLITUD** 

Medida de la variación máxima del desplazamiento de la onda senoidal en el tiempo.
* **VALOR PICO (Vp)**

Es el valor máximo que alcanza la señal senoidal.
* **VALOR PICO A PICO (Vpp)**

Magnitud entre el valor de pico positivo y el negativo, es decir, el doble del valor pico.
* **PERÍODO** 

Tiempo que la onda necesita para completar un ciclo, se mide en segundos y la podemos calcular de dos formas: dividiendo 1 sobre la frecuencia y diviendo 2π sobre la velocidad angular (w).
* **FRECUENCIA**

Cantidad de ciclos que se repiten en un segundo, se mide en Hertz, y la podemos calcular de dos formas: dividiendo 1 sobre el período y diviendo la velocidad angular(w) sobre 2π.
* **VALOR RMS O VALOR EFICAZ** 

Se denomida valor rms al valor que tendrá una corriente continua para producir la misma potencia en corriente alterna sobre la misma resistencia.
  
![](https://github.com/BriandaLema/Laboratorio7/blob/master/img/Caracter%C3%ADsticas%20de%20la%20onda%20senoidal.png)

**1** - Valor pico.

**2** - Valor pico a pico.

**3** - Valor rms.

**4** - Período.

## 4. DIAGRAMAS

Se simula un circuito lineal, es un circuito con dos resistencias en serie conectadas a un generador de funciones.

![](https://github.com/BriandaLema/Laboratorio7/blob/master/img/Diagrama%201.png)

Circuito en el simulador Multisim.

![](https://github.com/BriandaLema/Laboratorio7/blob/master/img/Diagrama%202.jpeg)



## 5. LISTA DE COMPONENTES

| CANTIDAD| ELEMENTO |
| ------- | -------------|
| 1       | Generador de funciones  |
| 1       | Osciloscopio  |
| 1       | Multímetro digital   |
| 1       | Resistor de 1 kΩ   |
| 1       | Resistor de 2.2 kΩ  |
| 1       | Protoboard|

## 6. MAPA DE VARIABLES 

Variables eléctricas: 

* Voltaje

## 7. EXPLICACIÓN CÓDIGO DE FUENTE

Para este laboratorio utilizamos el simulador de Tinkercad , el cual es un sofware de diseño de circuitos, en este dispositivo encontramos una gama alta de componentes electrónicos que se utilizan para la creación de circuitos y simular su funcionamiento.
Tinkercad funciona directamente en un navegador web moderno por lo cual una conexión a internet es fundamental para la utilización de esta fuente. 
El mismo programa nos guía y asesora acerca de lo que realizamos, por lo cual la utilizacion de esta fuente es muy práctica si tienes un conocimiento básico sobre circuitos eléctricos.Una herramienta característica de Tinkercad es quemientras la simulación está en marcha podemos ir modificando las variables de cada elemento y ver los cambios en el momento. También podemos obtener una lista con los materiales empleado  que nos sirvio para realizar las fichas técnicas.



## 8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Fundamentalmente los prerrequisitos que requiere este laboratorio sería: un dispositivo tegnológico (sea un teléfono, una pc, un tableta, entre otras); pues trabajamos en un simulador online, nuestro segundo requisito es acceso a internet y finalmente tener conocimientos básicos sobre las leyes aplicadas, los componentes, elementos y variables que se utiliza para la creación y el siguiente análisis del circuito.

**PREGUNTAS**

**1. ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?**

Observando la gráfica que nos proporciona el osciloscopio se podría decir que la amplitud pico de la señal de salida abarca 3 cuadros y medio.

**2. ¿En qué valor está posicionada la perilla VOLTS/DIV?**

La perilla VOLTS/DIV está posicionada en 2 V.

**3. ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?**

Observando la gráfica que nos proporciona el osciloscopio se podría decir que ciclo completo de la señal de salida abarca 2 cuadros.

**4. ¿En qué valor está posicionada la perilla TIME/DIV?**

La perilla TIME/DIV está posicionada en 200 μs.

**5. ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?**

Amplitud de voltaje: 6.75 (V)

Periodo: 0.0004 (s)

**6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.**

f: 2500 (Hz)

ω: 15707.96 (rad/s)

**7. Con el multímetro digital mida el voltaje de salida en RL.**

Voltaje en RL: 4.861 V

**8. Compare el voltaje medido en el punto 5 y el obtenido en el punto 7. ¿Coinciden? ¿Por qué?**

No coinciden, debido a que el valor de 6.75 V es el valor pico de que dispone la resistencia 2.2k y 4.861 V es el valor rms que dispone está misma.

**CÁLCULO DEL ERROR**

Voltaje pico en RL: 4.861 V * x {\displaystyle x}

* **VTH (V)**

| CALCULADO | MEDIDO  | 
|----------|------|
| 5.06 V | 5.0556 V |

* **RTH Ω**

| CALCULADO | MEDIDO  | 
|----------|------|
| 299 Ω | 298.86 Ω |


%error= 1.30 % 

- **CÁLCULO DEL ERROR DE LA CORRIENTE EN R5 EN EL CIRCUITO EQUIVALENTE DE THÉVENIN**

Voltaje calculado= 3.84 mA

Voltaje medido= 3.89 mA

%error=(|(Valor teórico-Valor medido)|/Valor teórico)* 100

%error=(|(3.84 mA - 3.89 mA)|/ 3.84 mA )* 100

%error= 1.30 % 


## 9.APORTACIONES

Para complementar la correcta cuantificacion de valores calculados y valores medidos se baso en videos de la plataforma online YouTube, y se implemento el circuito en el simulador multisim para confirmar los valores.

## 10. CONCLUSIONES

Concluimos que el osciloscopio es una herramienta importante que nos permite graficar distintos tipos de señales de tipo sinusioidal, cuadrada triangular, en nuestro caso esencialmente la sinusoidal y al mismo tiempo nos permite calcular variables como voltaje o periodo de la señal

El generador de señales se encuentra relacionado directamente con el osciloscopio ya que permite generar distintos tipos de señales que se grafican en el osciloscopio, la cual nos permite mayor obtención de los datos requeridos. 

Con esta prática hemos aprendido acerca de las funciones que presenta el generador de señales y la graficación que nos permite visualizar el osciloscopio, con esto podemos comprender los conceptos adquiridos.


## 11. RECOMENDACIONES

Recomendamos la previa conceptualización de los componentes del tema para una correcta medición y toma de valores de manera ordenada con el fin de no cometer errores teniendo como finalidad un error excesivo. 

Se debe tomar a consideración el graficar correctamente el circuito y transcribir correctamente los valores de la fuente, caso contrario no se logrará llegar a un objetivo y una comprobación. 

Sugerimos acordarse que para calcular el voltaje de una resistencia, el multímetro se lo conectará en paralelo a la misma, también se recomienda la correcta conexión del osciloscopio para tener una adecuada lectura y gráfica de la señal sinusoidal.


## 12. CRONOGRAMA

![](https://github.com/BriandaLema/Laboratorio7/blob/master/img/LAB7.png)

https://trello.com/b/psrtdBrJ/laboratorio-7


## 13. BIBLIOGRAFÍA

* Anónimo. (29 de 08 de 2019). EcuRed. Obtenido de https://www.ecured.cu/Onda_senoidal
* Anónimo. (01 de 09 de 2015). Obtenido de https://es.slideshare.net/vr3220/caractersticas-de-la-onda-senoidal
* Zapata, F. (s.f.). lifeder.com. Obtenido de https://www.lifeder.com/onda-senoidal/





## 14.- ANEXOS
https://github.com/BriandaLema/Laboratorio7/blob/master/Anexos/ANEXOS_7.pdf







