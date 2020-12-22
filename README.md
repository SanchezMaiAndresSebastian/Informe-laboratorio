# Informe de Laboratorio 1
## Leyes de Kirchoff
### 1.	OBJETIVOS

**Principales**

 -	Experimentar con las Leyes de Kirchhoff
 - Construir un circuito

**Específicos**

- Distinguir entre lo que es corrinete y voltaje
- Investigar lo que es la leyes de Kirchoff

### 2.	MARCO TEÓRICO 
Los circuitos no siempre se pueden reducir a circuitos sencillos (serie y paralelo). Se tiene que utilizar nuevas leyes para resolver el circuito: lo que significa que dadas las unidades de los generadores, sus resistencias internas y las resistencias externas debemos encontrar las intensidades en cada rama del circuito. 
Un nodo es un punto del circuito donde tres o más conductores concurren. En el nodo, como consecuencia de la conservación de la carga, la suma de las intensidades que llegan es igual a la suma de las intensidades que salen, o sea:
Por ejemplo, en la siguiente figura se tiene:  
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/1.png)
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/2.png)

FIGURA 1 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/3.png)


Una malla  es una trayectoria conductora cerrada, Para la malla de la siguiente figura calculamos la diferencia de potencial en cada rama:ç

FIGURA 2

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/4.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/5.png)

Sumando miembro a miembro y ordenando, se tiene    

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/6.png)

Lo anterior se puede escribir como:       

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/7.png)

Es de notar que la relación anterior es una consecuencia de la conservación de la energía, ya que la relación nos da la diferencia de potencial entre dos puntos de un circuito, se demuestra a partir de un balance de energía.

Procedimiento.
Armamos el siguiente circuito:

FIGURA 3

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/8.png)


Medida la corriente y el voltaje en cada uno de los resistores y compárelos con los valores teóricos. Complete la tabla de la hoja de informes en esta práctica.
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

###### _FIGURA 5_

> 5.1 Calculos de forma teorica

- Calcular la corriente en las mallas
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/14.png) 

- Calcular el voltaje 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/15.png)

- Calcular La corriente de los nodos

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/16.png) 

- Calculo del error porcentual

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/17.png) 

5.2 Tabulacion de los datos

5.2.1 Resultados obtenidos de voltaje y corriente, en cada elemento del circuito. 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/18.png) 

Tabla 1

5.2.2 Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada,
considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con
signo negativo. Anote los resultados en la tabla 1

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/19.png) 

Tabla 2

5.2.3 Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando
con signo positivo las corrientes que entran al nodo y con signo negativo las que salen
del nodo. Anote los resultados en la tabla 2.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/20.png) 

Tabla 3

5.2.4 Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/21.png) 

Tabla 4

5.2.5 Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.

En el circuito que hemos construido se ve como la unión de diferentes elementos eléctricos en un circuito eléctrico, el cual primero se pone la fuente de voltaje de corriente continua se une con alambres el color perteneciente a su fuente con el protoboard el cual es el positivo (rojo) y el negativo (negro)
Después se pone con el resistor en la parte de los nodos en la columna que sea necesario para que tenga un paso de corriente
Terminamos midiendo el voltaje de cada resistor 

### 6.	 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

 - Siempre tener conectado a una fuente de corriente continua
 - Tener la fuente de voltaje configurada para la medición en voltios
 - Tener el multímetro siempre en la configurada en la medición de voltios 
 
### 7.	APORTACIONES

 - No hay paso de corriente si se invierten la tomas positivas y negativas de un circuito,
 - No es lo mismo la medición de voltaje con corriente 
 - El multímetro tiene diferentes funcionamientos dependiendo si es digital o análogo
 
### 8.	CONCLUSIONES
 - Se demostro que las leeys de lkirchoff se rigen bajo los nodos que con ello se experimenta con los circuitos por ende siempre van a tener mediciones en cualquier parte del proyecto.
 -Al momento de construir el circuito se tiene que tener en cuenta que tiene que conectarse correctamenet los cabls en el positivo y negativo de todos los instrumentos electricos los cuales si no se hacen correctamente pueden sufrir una disminución de la vida útil.


### 9.	BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos electricos. Mexico: Pearson Educacion. Serway,

R. (2001). Fisica II. Mexico: Pearson Educacion.
### 10.	 ANEXOS

