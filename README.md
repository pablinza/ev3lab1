# EV3LAB1 pablinza@me.com
Programación del modulo Lego Mindstorm EV3 con lenguaje __micropython__ [--> Sitio Oficial](https://education.lego.com/es-es/product-resources/mindstorms-ev3/teacher-resources/python-for-ev3/) <br />
Lego Mindstorm es un kit completo que en su tercera generación EV3 fue distribuida en dos Ediciones: el set __HOME (31313)__ y el set __EDUCATION (45544)__ en ambos el cerebro principal __Brick EV3__ esta basado en un Microprocesador TI AM1808 arquitectura ARMv9. Por defecto el modulo EV3 corre una versión especial de linux que permite la programación gráfica por bloques (EV3 Classroom) utilizando una capa intermedia basada en Python. El modulo cuenta con conectividad USB, Bluetooth y 8 puertos E/S para los diferentes sensores que se incluyen en el kit. <br />
<br />
Este repositorio contiene código de los programas desarrollados con __EV3 Python__(Pybrick) para cada maquina o robot construido en el laboratorio. Comentar que se describen ejemplos básicos enfocados al aprendizaje en la etapa escolar como complemento a la programación en bloques realizados con __EV3 Classroom__. <br />
El IDE utilizado para la programación es __Visual Code__ disponible de forma gratuita en su sitio oficial [ --> Click](https://code.visualstudio.com/) <br />
Las instrucciones para descargar e instalar el interprete micropython en __EV3 Python__ están en el siguiente enlace [ --> Click](https://education.lego.com/es-es/product-resources/mindstorms-ev3/teacher-resources/python-for-ev3/) <br />

En resumen, una vez descargado el firmware, debes descomprimir y copiar el archivo de imagen a una tarjeta microSD de al menos 4GB de capacidad, para este paso yo utilice la aplicación __ISO Image Writter__, lo bueno de todo esto es que no modificaras el firmware por defecto que tiene tu modulo EV3 (EV3 Classroom) ya que el interprete Python correrá solo cuando insertas la tarjeta SD. Para empezar la programación solo necesitaremos conectar el modulo a la PC con un cable USB. <br />

## Configuración del Modulo EV3 con Python
En el siguiente enlace [--> Click](https://youtu.be/wHSbDzvcbXE) dejo un vídeo que muestra la preparación del __EV3 Python__ para su programación con el IDE __Visual Code__, la creación de un programa inicial y prueba de sensores-actuadores.
<p align="center">
  <img src="/images/ev3kit.png"></img>
</p> <br />

</p>
Todos los puertos de entrada y salida tienen capacidades y una configuracion similar, por lo un sensor o actuador puede conectarse a cualquier puerto, eso si respetando que sea una entrada o salida. Incluso los puertos de salida contiene lineas de entrada como realimentación del control en lazo cerrado. Aquí dejo una descripción de los pines que resume la funcionalidad:
<br />
</p>

| PIN RJ-12| PUERTO DE ENTRADA | PUERTO DE SALIDA |
|----------|:-------------:|------:|
| 1 | ADC/TC | PWM+ |
| 2 | GND | PWM- |
| 3 | GND | GND |
| 4 | +5V | +5V |
| 5 | SCL/IN1 | ENCA |
| 6 | SCK/IN2 | ENCB |

<br clear="center"/>
Autor: Pablo Zarate, puedes contactarme a pablinza@me.com / pablinzte@gmail.com.  <br />
Visita mi Blog  [Blog de Contenidos](https://pablinza.blogspot.com/). <br />
Visita mi Canal [Mi canal Youtube](http://www.youtube.com/@pablozarate7524). <br />
Santa Cruz - Bolivia 
<br clear="left"/>
