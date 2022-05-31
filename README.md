# Informe de Laboratorio 1
## Leyes de Kirchoff
### 1.	OBJETIVOS

**Principales**

 - Construir un circuito en el simulador Tinkercad de donde se extraerá los datos de las mediciones basándonos en las leyes de Kirchhoff.

**Específicos**

- Distinguir los conceptos de corriente y voltaje
- Investigar lo que es las leyes de Kirchoff
- Diferenciar las partes de una herramienta eléctrica
- Conocer cómo funciona el multímetro
- Consultar la nomenclatura de colores y valores parar las resistencias.

### 2.	MARCO TEÓRICO 
Los circuitos no siempre se pueden reducir a circuitos sencillos (serie y paralelo). Se tiene que utilizar nuevas leyes para resolver el circuito: lo que significa que, dadas las unidades de los generadores, sus resistencias internas y las resistencias externas debemos encontrar las intensidades en cada rama del circuito. 
Un nodo es un punto del circuito donde tres o más conductores concurren. En el nodo, como consecuencia de la conservación de la carga, la suma de las intensidades que llegan es igual a la suma de las intensidades que salen, o sea:
Por ejemplo, en la siguiente figura se tiene:  
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/1.png)
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/2.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/3.png)

###### _FIGURA 1_

Una malla es una trayectoria conductora cerrada, Para la malla de la siguiente figura calculamos la diferencia de potencial en cada rama


![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/4.png)

###### _FIGURA 2_

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/5.png)


Sumando miembro a miembro y ordenando, se tiene    

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/6.png)

Lo anterior se puede escribir como:       

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/7.png)

Es de notar que la relación anterior es una consecuencia de la conservación de la energía, ya que la relación nos da la diferencia de potencial entre dos puntos de un circuito, se demuestra a partir de un balance de energía.

Procedimiento.
Armamos el siguiente circuito:

__Resistores__

En todas las resistencias nos podeos encontrar características, el valor nominal expresado en ohms (Ω), la tolerancia en % y la potencia en vatios (W).

- Valor nominal: Es el que indica el fabricante. Este valor normalmente es diferente del valor real, pues influyen diferentes factores de tipo ambiental o de los mismos procesos de fabricación, pues no son exactos. Suele venir indicado, bien con un código de colores, bien con caracteres alfanuméricos.

- Tolerancia: Debido a los factores indicados anteriormente, y en función de la exactitud que se le dé al valor, se establece el concepto de tolerancia como un % del valor nominal. De esta forma, si nosotros sumamos el resultado de aplicar el porcentaje al valor nominal, obtenemos un valor límite superior. Si por el contrario lo que hacemos es restarlo, obtenemos un valor límite inferior. Con la tolerancia, el fabricante nos garantiza que el valor real de la resistencia va a estar siempre contenido entre estos valores, Si esto no es así, el componente está defectuoso.

- Potencia nominal: Es el valor de la potencia disipada por el resistor en condiciones normales de presión y temperatura.

__Clasificación de Resistores__

Como ya se indicó con anterioridad, una de las formas de indicar el valor nominal de una resistencia es mediante un código de colores que consta, como norma general, de 3 bandas de valor y una de tolerancia.

El código empleado es el siguiente:

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/30.jpg)

###### _FIGURA 3_

Medida la corriente y el voltaje en cada uno de los resistores y compárelos con los valores teóricos. Complete la tabla de la hoja de informes en esta práctica.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/30.png)

### 3.	DIAGRAMAS

- Diagramas eléctricos

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/49.png)
 
 - Diagramas esquemáticos.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/54.png) 



### 4.	LISTA DE COMPONENTES

| Cantidad | Componentes | 
| -------- | ----------- | 
| 1 |Protoboard | 
| 1 |Fuente de voltaje de C.D. | 
| 1 |Multímetro | 
| 1 |Resistencia 1 kΩ | 
| 2 |Resistencia 2,2 kΩ | 
| 1 |Resistencia 1,8 kΩ | 
| 1 |Resistencia 3,9 kΩ | 
 
> (Herramientas utilizadas en simulación) 
> Simulador Thinkercad


### 5.	EXPLICACIÓN

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/44.png) 

Se hace una separación de las herramientas que vamos a usar durante está practica

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/45.png) 

Se pone los resistores como se muestra en el diagrama eléctrico dentro de la placa de pruebas.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/46.png) 

Se conecta con alambras los resistores para que sea un circuito cerrado.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/47.png) 

Para medir el voltaje de cada uno de los elementos resistivos se debe de conectar el multímetro de forma que forme un circuito en paralelo.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/48.png) 

Para medir la corriente de cada uno de los elementos resistivos se debe de conectar el multímetro de forma que forme un circuito en serie.

### 6. MANUAL DE USUARIO

### 7.	DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

 - Siempre tener conectado a una fuente de corriente continua
 - Tener la fuente de voltaje configurada para la medición en voltios
 - Tener el multímetro siempre en la configurada en la medición de voltios 
 
### 8.	APORTACIONES

__8.1__ Tabulación de los datos

__8.1.1__ Resultados obtenidos de voltaje y corriente, en cada elemento del circuito. 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/50.png) 

Tabla 1

__8.1.2__ Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada,
considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con
signo negativo. Anote los resultados en la tabla 1

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/51.png) 

Tabla 2

__8.1.3__ Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando
con signo positivo las corrientes que entran al nodo y con signo negativo las que salen
del nodo. Anote los resultados en la tabla 2.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/52.png) 

Tabla 3

__8.1.4__ Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/53.png) 

Tabla 4

__8.1.5__ Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.



En el circuito que hemos construido se ve como la unión de diferentes elementos eléctricos en un circuito eléctrico, el cual primero se pone la fuente de voltaje de corriente continua se une con alambres el color perteneciente a su fuente con el protoboard el cual es el positivo (rojo) y el negativo (negro)
Después se pone con el resistor en la parte de los nodos en la columna que sea necesario para que tenga un paso de corriente
Terminamos midiendo el voltaje de cada resistor 
 .
 
### 9.	CONCLUSIONES
 - Se demostró que las leyes de Kirchhoff se rigen bajo los nodos que con ello se experimenta con los circuitos por ende siempre van a tener mediciones en cualquier parte del circuito elaborado.
 - Al momento de construir el circuito se debe tener en cuenta que tiene que conectarse correctamente los terminales en el positivo y negativo de todos los instrumentos eléctricos los cuales si no se utiliza correctamente pueden sufrir una disminución de la vida útil de la herramienta.
 - Cuando se está midiendo el corriente de un resistor en el multímetro, cambia el valor de la corriente de los demás resistores que se tienen midiendo con las demás herramientas en el mismo tiempo.
 - Las resistencias que se utilizan en el simulador no tiene margen de error de los valores obtenidos.
 - Las herramientas de medición de corriente y voltaje son idóneos, es decir que no presentan errores de medición a causa de los materiales que están elaborados.
 - No hay paso de corriente si se invierten la tomas positivas y negativas de un circuito.
 - No es lo mismo la medición de voltaje con corriente 
 - El multímetro tiene diferentes funcionamientos dependiendo si es digital o análogo.
 - La fuente de corriente directa mide cuantos amperios tiene el circuito

### 10.	BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. México: Pearson Educacion. Serway,

R. (2001). Física II. México: Pearson Educacion.

### 11.	 ANEXOS

https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/55.jpg
https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/56.jpg
https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/57.jpg
