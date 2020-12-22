# Informe de Laboratorio 1
## Leyes de Kirchoff
### 1.	OBJETIVOS

**Principales**

 -	Experimentar con las Leyes de Kirchhoff y los circuitos mixtos.
 - Construir un circuito.

**Específicos**

- Distinguir entre lo que es corriente y voltaje
- Investigar lo que es la leyes de Kirchoff
- Diferenciar las partes de una herramienta electrica
- Concocer como funciona el multimetro
- Consultar la nomenclatura de colores y valores parar las resistencias.

### 2.	MARCO TEÓRICO 
Los circuitos no siempre se pueden reducir a circuitos sencillos (serie y paralelo). Se tiene que utilizar nuevas leyes para resolver el circuito: lo que significa que dadas las unidades de los generadores, sus resistencias internas y las resistencias externas debemos encontrar las intensidades en cada rama del circuito. 
Un nodo es un punto del circuito donde tres o más conductores concurren. En el nodo, como consecuencia de la conservación de la carga, la suma de las intensidades que llegan es igual a la suma de las intensidades que salen, o sea:
Por ejemplo, en la siguiente figura se tiene:  
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/1.png)
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/2.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/3.png)

###### _FIGURA 1_

Una malla  es una trayectoria conductora cerrada, Para la malla de la siguiente figura calculamos la diferencia de potencial en cada rama:ç


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

En todas las resistencias nos podemos encontrartres características, el valor nominal expresado en ómios (W), la tolerancia en % y la potencia en vatios (W).

- Valor nominal: Es el que indica el fabricante. Este valor normalmente es diferente del valor real, pues influyen diferentes factores de tipo ambiental o de los mismos procesos de fabricación, pues no son exactos. Suele venir indicado, bien con un código de colores, bien con caracteres alfanuméricos.

- Tolerancia: Debido a los factores indicados anteriormente, y en función de la exactitud que se le de al valor, se establece el concepto de tolerancia como un % del valor nominal. De esta forma, si nosotros sumamos el resultado de aplicar el porcentaje al valor nominal, obtenemos un valor límite superior. Si por el contrario lo que hacemos es restarlo, obtenemos un valor límite inferior. Con la toelrancia, el fabricante nos garantiza que el valor real de la resistencia va a estar siempre contenido entre estos valores, Si esto no es así, el componente está defectuoso.

- Potencia nominal: Es el valor de la potencia disipada por el resistor en condiciones normales de presión y temperatura.

__Clasificación de Reistores__

Como ya se indicó con anterioridad, una dels formas de indicar el valor nominal de una resistencia es mediante un código de colores que consta, como norma general, de 3 bandas de valor y una de tolerancia.

El código empleado es el siguiente:

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/30.jpg)

###### _FIGURA 3_

Medida la corriente y el voltaje en cada uno de los resistores y compárelos con los valores teóricos. Complete la tabla de la hoja de informes en esta práctica.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/30.png)

### 3.	DIAGRAMAS

- Diagrama de bloques

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/9.png)

- Diagramas UML

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/10.png)

- Diagramas eléctricos

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/11.png)
 
 - Diagramas esquemáticos.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/12.png) 



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
> Simulador thinkercad


### 5.	EXPLICACIÓN
Aramar el circuito

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/13.png) 

###### _FIGURA 4_

__5.1__ Calculos de forma teorica

- Calcular la corriente en las mallas
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/14.png) 

- Calcular el voltaje 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/15.png)

- Calcular La corriente de los nodos

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/16.png) 

- Calculo del error porcentual

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/17.png) 

__5.2__ Tabulacion de los datos

__5.2.1__ Resultados obtenidos de voltaje y corriente, en cada elemento del circuito. 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/18.png) 

Tabla 1

__5.2.2__ Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada,
considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con
signo negativo. Anote los resultados en la tabla 1

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/19.png) 

Tabla 2

__5.2.3__ Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando
con signo positivo las corrientes que entran al nodo y con signo negativo las que salen
del nodo. Anote los resultados en la tabla 2.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/20.png) 

Tabla 3

__5.2.4__ Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/21.png) 

Tabla 4

__5.2.5__ Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.



En el circuito que hemos construido se ve como la unión de diferentes elementos eléctricos en un circuito eléctrico, el cual primero se pone la fuente de voltaje de corriente continua se une con alambres el color perteneciente a su fuente con el protoboard el cual es el positivo (rojo) y el negativo (negro)
Después se pone con el resistor en la parte de los nodos en la columna que sea necesario para que tenga un paso de corriente
Terminamos midiendo el voltaje de cada resistor 

### 6.	 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

 - Siempre tener conectado a una fuente de corriente continua
 - Tener la fuente de voltaje configurada para la medición en voltios
 - Tener el multímetro siempre en la configurada en la medición de voltios 
 
### 7.	APORTACIONES

 - No hay paso de corriente si se invierten la tomas positivas y negativas de un circuito.
 - No es lo mismo la medición de voltaje con corriente 
 - El multímetro tiene diferentes funcionamientos dependiendo si es digital o análogo.
 - LLa fuente de corriente directa mide cuantos amperios tiene el circuito.
 
### 8.	CONCLUSIONES
 - Se demostro que las leeys de lkirchoff se rigen bajo los nodos que con ello se experimenta con los circuitos por ende siempre van a tener mediciones en cualquier parte del proyecto.
 - Al momento de construir el circuito se tiene que tener en cuenta que tiene que conectarse correctamenet los cabls en el positivo y negativo de todos los instrumentos electricos los cuales si no se hacen correctamente pueden sufrir una disminución de la vida útil.
 - Cuando en unn resistor se encuentra aplicado con el multímetro la medicion de su corriente, cambia el voltaje de los demas resistores que se tienen midiendo con los demás herraminetas

### 9.	BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos electricos. Mexico: Pearson Educacion. Serway,

R. (2001). Fisica II. Mexico: Pearson Educacion.
### 10.	 ANEXOS


![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/22.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/23.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/24.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/25.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/26.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/28.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/29.png)

