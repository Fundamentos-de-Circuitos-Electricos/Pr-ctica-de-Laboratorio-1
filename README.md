![image](https://user-images.githubusercontent.com/84390820/120706807-2aa0bd00-c47f-11eb-9ca7-ba590d62db62.png)


________________________________________________________________________________
# Informe de Laboratorio 

1. OBJETIVOS

General

* Investigar las Leyes de Kirchhoff de voltaje y de corriente mediante documentos de información teórica de eléctrica y electrónica para el análisis de circuitos y su aplicación en mallas, ramas, nodos o en cada uno de los componentes pasivos o activos como resitores, capacitores o inductores en los distintos tipos de circuitos como serie y paralelo. 

Específicos

* Conocer las definiciones de nodo, rama y malla en los tipos de circuitos eléctricos. 

* Interpretar y aplicar las Leyes de Kirchhoff en circuitos paralelos y en serie.

* Calcular mediante leyes de Kirchhoff la intensidad y voltajes de los elementos de circuitos.  


2. MARCO TEORICO

![image](https://user-images.githubusercontent.com/84390820/120563854-3339ba80-c3cf-11eb-89db-2ca3a1e8c4ea.png)



3. EXPLICACIÓN DEL PROCEDIMIENTO
 
 * Material y equipo requerido
 
![image](https://user-images.githubusercontent.com/84390820/120563174-962a5200-c3cd-11eb-8449-4e8707230eeb.png)

 * Armado del circuito
 
Procedimiento

1. Colocar, un siministro de energía de 10 volts.

![image](https://user-images.githubusercontent.com/84390820/120701760-df83ab80-c478-11eb-9320-5eebb39ff753.png)

2. Escoger correctamente los resistores con su codificación de colores. 

![image](https://user-images.githubusercontent.com/84390820/120701782-e7dbe680-c478-11eb-97d5-e95d1d3b08d9.png)

3. Conectar el circuito mediante el diagrama de conexión.

* Diagrama esquemático

![image](https://user-images.githubusercontent.com/84390820/120702231-73ee0e00-c479-11eb-9351-446153b76fbb.png)

* Conexión del circuito

![image](https://user-images.githubusercontent.com/84390820/120701875-09d56900-c479-11eb-97a7-3e5200bcc107.png)


4. Procedemos a medir los valores de voltaje y corriente de los elementos pasivos del circuito. Utilizamos como instrumento de medida un multímetro.   


![image](https://user-images.githubusercontent.com/84390820/120705034-eb716c80-c47c-11eb-9d3c-8f29e3d22d00.png)

A continuación calculamos los valores teóricos de corriente y voltaje de los elementos pasivos, para completar la siguiente tabla: 

Aplicamos la Ley de Mallas de Kirchhoff

![image](https://user-images.githubusercontent.com/84390820/120714766-414c1180-c489-11eb-8e59-3254bf3d4bf1.png)

Planteamos la ecuación de la Malla de I1 

1kΩ· I1 + 3.9kΩ· I1 + 1.8kΩ· I1 - 3.9kΩ· I2 = 10

Planteamos la ecuación de la Malla de I2 

2.2kΩ· I2 + 2.2kΩ· I2 + 3.9kΩ· I2 - 3.9kΩ· I1 = 0

Simplificamos las ecuaciones

1)	6.7kΩ· I1 - 3.9kΩ· I2 = 10

2)	-3.9kΩ· I1 + 8.3kΩ· I2 = 0

Resolvemos el sistema de ecuaciones por método de reducción de Gauss Jordan, obteniendo como resultado: 

I1 = 2.05 mA

I2 = 0.965 mA     

Por último, definimos una tercera ecuación en la cual sería por la Ley de Nodos de Kirchhoff. Las corrientes que entran a un nodo son iguales a las corrientes que salen. 

Entonces, I1 = I2 + I3 

Para encontrar I3 despejamos de la ecuación

I3 = I1 – I2 = 2.05 mA - 0.965 mA = 1.09 mA    




