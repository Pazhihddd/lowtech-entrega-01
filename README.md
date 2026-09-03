#  Lowtech-entrega-01

## Monitoreo de la Calidad del Agua en Trafampulli.
### Proyecto de diseño y monitoreo ambiental.

### Lugar: Sector de Trafampulli, Región de La Araucanía.
### Tema: Calidad del agua.
### Objetivo general: Hacer visibles posibles cambios en las características del agua utilizada por los habitantes del sector.

### Estudiantes Paz Haddad, Serena Loi
### Electivo Mención I y S: Dispositivos Low-Tech e Interfaces Interactivas.
### Profesor Ricardo Sepúlveda S.

---

## Fenómeno

En la región de La Araucanía, cerca del lago Colico, hay un sector de vecinos cuya única fuente de agua potable es la que cae de la cordillera, donde a veces al ser caída de la cordillera de forma directa, se ve contaminado ya sea de forma natural, como artificial. Lo que interviene tanto en el ganado como en la agricultura particular de los vecinos de la zona, siendo estos sus mayores ingresos o sustentos económicos.

El fenómeno que buscamos observar corresponde a las variaciones en la calidad del agua, las cuales no siempre pueden identificarse a simple vista. Aunque el agua pueda parecer limpia, algunas de sus características, como su nivel de acidez, alcalinidad o concentración de sólidos disueltos, pueden cambiar.

---

## Contexto / Usuario

¿Dónde ocurre?
En el sector de Trafampulli, en la región de La Araucanía

¿A quién afecta?
A los vecinos que viven en el sector

¿Qué prácticas, cuerpos, plantas, ambientes o comunidades están involucradas?
- El consumo de agua de los habitantes.
- La hidratación de animales y ganado.
- El riego de cultivos.
- El suelo destinado al cultivo.
- El ecosistema que rodea las fuentes de agua.


### Fenómeno / problema

¿Qué condición queremos observar o hacer visible?
Queremos monitorear la pureza del agua y/o los químicos y alteraciones de esta 

¿Por qué importa?
Porque es el único acceso a agua que tiene la gente que vive en este sector, y no saben cuando está contaminada o no, y si el valor de la cantidad de los cambios hace que el agua se vuelva peligrosa.


¿Qué tensión aparece?
La necesidad de utilizar diariamente esta fuente de agua y la dificultad de conocer de manera sencilla y constante cuál es su calidad. Los habitantes dependen de ella para sus actividades cotidianas, pero no necesariamente cuentan con herramientas accesibles que permitan detectar cambios o posibles alteraciones antes de utilizarla.


### Variable / hipótesis


¿Qué podemos medir u observar?
Podemos medir la pureza del agua, los químicos presentes en esta, el nivel de pH, y cómo afectan los diferentes minerales a la tierra


¿Qué tipo de dispositivo podría traducirlo en experiencia, dato o acción?
Se puede usar un mededidor de pH y un medidor TDS

---

## Referentes

1. El medidor de conductividad eléctrica (TDS / EC Meter) utiliza dos puntas metálicas (a menudo de titanio o acero) para hacer pasar una microcorriente a través del agua.Qué mide: La cantidad de sólidos y minerales disueltos (determina si el agua está pura o "sucia"). Existen versiones de bolsillo (en forma de bolígrafo). Requieren una pequeña batería de botón, pero las puntas metálicas no se desgastan y no se necesitan líquidos de calibración complejos para mediciones generales.

2. El probador de electrólisis es una herramienta de baja tecnología formidable para demostraciones. Tiene cuatro barras de metal (dos de hierro y dos de aluminio) que se sumergen en los vasos de agua.Cómo funciona: Se conecta a la toma de corriente durante unos pocos segundos. La corriente viaja entre las puntas metálicas utilizando las sales químicas presentes en el agua como conductor.El resultado: El agua cambiará de color drásticamente. Se volverá verde oscuro/negra si hay metales pesados, amarilla si hay ácidos, o se mantendrá transparente si el agua es destilada o purísima.
   
3. En casa se puede construir un circuito con una bombilla LED, una batería de 9V, dos clavos de metal (uno de cobre y uno de zinc/hierro galvanizado).Si sumerges los dos clavos en el agua sin que se toquen entre sí: cuanto más rica sea el agua en sustancias químicas y sales, más intensamente se encenderá la bombilla gracias a la conductividad del líquido. Si el agua es purísima, la luz se quedará apagada.

4. Los medidores de pH profesionales o de laboratorio basados en el electrodo de bulbo de vidrio. Su funcionamiento no se basa en una reacción química visual, sino en un principio físico-eléctrico llamado intercambio iónico. El pH depende de cuántos "iones de hidrógeno" hay en el agua (mientras más haya, más ácida es el agua). Cuando sumerges la ampolla, los iones presentes en el agua se adhieren a la parte externa del vidrio.

---

## Variables

Variación de las características físico-químicas del agua.
Para aproximarnos a esta variable observaremos principalmente:
pH:
Permite observar cambios relacionados con la acidez o alcalinidad del agua.
TDS:
Permite estimar la cantidad de sólidos disueltos presentes en el agua

El objetivo no es determinar qué tiene el agua exactamente, sino que determinar si esta presenta variaciones o no

---

## Hipótesis

Si medimos periódicamente las variables del agua, podremos identificar cambios en las características habituales y hacer visibles posibles alteraciones para los habitantes de Trafampulli.

Se propone desarrollar un kit de monitoreo Low-Tech de agua que pueda ser utilizado de manera sencilla por los habitantes del sector.

Se puede realizar un sensor racuidado en una caja. Este sensor podría tener la placa Arduino Uno, el alimentador externo como una batería, el kit de sensor de pH analógico que incluye la sonda de vidrio negra con conector redondo y la tarjeta electrónica de interfaz a la que se atornilla la sonda y que envía la señal a Arduino, y el kit de sensor TDS analógico que incluye la sonda de plástico impermeable con las dos puntas metálicas internas y su tarjeta de amplificación de la señal.

- Los vecinos tomarán una muestra de agua 

- El dispositivo contará con un medidor de pH y TDS el cual medirá los cambios

- El sistema contará con 3 Luces LED que medirán si:
-   Verde si el agua no presenta cambios
-   Amarillo si el agua presenta cambios pero es potable
-   Rojo si no es apta para consumo 


