# InformeLaboratorio2

# 1 OBJETIVOS

Calcular cada corriente presente en el circuito mostrado mediante el método de análisis de mallas

**2.1. OBJETIVO DE LA PRÁCTICA**

*Comprender la aplicación de la ley de voltajes de Kirchhoff en circuitos mixtos .

*Verificar analitica y experimentalmente los valores de las corrientes indicadas 

*Comparar los resultados obtenidos  en los calculos teoricos y en los simuladores  y analizar si margen de error.


Comprobar experimentalmente el Análisis de Mallas.

**2.2. REQUISITOS PREVIOS.**

Se requiere el análisis analítico del circuito mostrado en la figura 2.1., mediante la técnica del análisis de mallas. El valor obtenido de cada corriente de malla anótelo en la
tabla 2.1.

**2.3. INFORMACIÓN GENERAL**

En el análisis de mallas se parte de la aplicación de KVL a un conjunto mínimo de
lazos para encontrar al final todas las corrientes de lazo. A partir de las corrientes
de lazo es posible encontrar todas las corrientes de rama. El número de lazos que
se pueden plantear en un circuito puede ser muy grande, pero lo importante es que
el sistema de ecuaciones represente un conjunto mínimo de lazos independientes. 

Este conjunto mínimo es cualquiera en el cual todos los elementos (ramas) hayan
sido tenidos en cuenta en al menos una malla. Las otras posibles mallas serán
entonces redundantes. Aquí también el número de incógnitas (corrientes de lazo)
debe ser igual al número de ecuaciones (una por malla del conjunto mínimo).
De acuerdo al tipo de circuito y la forma en que se seleccionen las mallas se
pueden tener distintas posibilidades de conexión de las fuentes:

• Fuentes de corriente controladas

• Fuentes de voltaje independientes

• Fuentes de voltaje controladas

• Fuentes de corriente independientes no compartidas por varias mallas

• Fuentes de corriente independientes compartidas por varias mallas

Según lo anterior hay varias maneras de resolver un circuito por el método de
mallas.
El método que llamaremos general aplica a los casos de circuitos con fuentes de
voltaje independientes y fuentes de corriente independientes no compartidas por
varias mallas. Este método NO aplica a los circuitos que tienen:

1. Fuentes de corriente independientes compartidas por varias mallas (se
usa el método de supermalla)

2. fuentes controladas de corriente o voltaje (se deben escribir las
ecuaciones de dependencia de la variable controlada y controladora)

Si el circuito solo tiene fuentes de voltaje independientes entonces se aplica el
método general por el sistema llamado de inspección.
El número mínimo de lazos independientes que hay que definir para tener un
sistema de ecuaciones linealmente independientes que se deben tener está dado
por la siguiente relación: 

# 2 MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/84430867/121817035-984da580-cc44-11eb-857b-fa04017c0925.png)

# 3 MATERIAL Y EQUIPO REQUERIDO

<div align="center">
     
|**CANTIDAD**|**MATERIAL O EQUIPO** |
|    :---:   |       :---:          | 
|      1     | Fuente de Voltaje de C.D. |
|      1     | Multímetro Digital |
|      1     | Multímetro Digital |
|      1     | Resistor de 390 Ω |
|      1     | Resistor de 1 kΩ |
|      1     | Resistor de 1.2 kΩ |
|      1     | Resistor de 2.2 kΩ |
|      1     | Protoboard |

</div>

# 4 EXPLICACIÓN DEL PROCEDIMIENTO

**2.5 PROCEDIMIENTO**

ANÁLISIS MATEMÁTICO

![circuito2](https://user-images.githubusercontent.com/84587172/121821823-1b7cf480-cc61-11eb-9d58-ab4d94c63a3e.png)

Para resolver el siguiente problema aplicaremos los siguientes pasos:

•	Identificamos las mallas y asignamos el sentido de las corrientes presentes en la mallas (sentido horario)

•	Finalmente calcularemos el valor de cada corriente presente en las mallas mediante la ley de voltajes de Kirchhoff con el fin de obtener las ecuaciones necesarias

<div align="center">
     
![M1](https://user-images.githubusercontent.com/84587172/121978046-fb2a6400-cd4c-11eb-9832-125a75f67596.png)

![M2](https://user-images.githubusercontent.com/84587172/121978051-fe255480-cd4c-11eb-8edc-ae9b3db9561f.png)

</div>

**2.5.1. Implemente el circuito que se presenta en la figura 2.1.**

![image](https://user-images.githubusercontent.com/84430867/121978207-4fcddf00-cd4d-11eb-9926-5948b1d8a240.png)

**2.5.2. Mida cada una de las corrientes de malla y anote los resultados en la tabla 2.1.**

![image](https://user-images.githubusercontent.com/84430867/121978138-2f058980-cd4d-11eb-95c1-b337528b2f7f.png)

**2.5.3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 2.1, obteniendo los valores de las corrientes de malla. Anote los resultados en la tabla 2.1.**

- Armando el circuito que se muestra en la figura 2.1

<div align="center">
     
![image](https://user-images.githubusercontent.com/84587293/121962587-8e07d600-cd2e-11eb-8143-c8d3426778ff.png)

</div>

- Seleccionamos los materiales para proceder armar el circuito.	

![2021-06-14 15_07_46-Circuit design Glorious Uusam _ Tinkercad](https://user-images.githubusercontent.com/84587293/121962795-d626f880-cd2e-11eb-9dc7-295fcfc571bd.png)

- Colocamos las resistencias al Protoboard siguiendo el diagrama espermático dado.

<div align="center">
     
![2021-06-14 15_13_36-Circuit design Terrific Crift-Bigery _ Tinkercad](https://user-images.githubusercontent.com/84587293/121962879-f060d680-cd2e-11eb-9b4f-1c550b53e5e3.png)

</div>

- Interconectamos las resistencias en el Protoboard siguiendo el circuito dado.

<div align="center">
          
![2021-06-14 15_27_31-Circuit design Terrific Crift-Bigery _ Tinkercad](https://user-images.githubusercontent.com/84587293/121962926-053d6a00-cd2f-11eb-938a-bb5c20cbc905.png)

</div>
     
- Conectamos el Protoboard a la fuente de alimentación (rojo+,negro -)e iniciamos la simulación con el circuito terminado.

![2021-06-14 16_11_59-Circuit design Terrific Crift-Bigery _ Tinkercad](https://user-images.githubusercontent.com/84587293/121962959-125a5900-cd2f-11eb-97fe-4d7bf6563829.png)

- Obteniendo los valores de las corrientes de malla. 

![2021-06-14 16_33_19-Circuit design Terrific Crift-Bigery _ Tinkercad](https://user-images.githubusercontent.com/84587293/121962993-1dad8480-cd2f-11eb-944b-40d2e1b87678.png)


**2.5.4. Compare los valores de la tabla 2.1 y realice sus conclusiones.**

**Calculo del Error**

![error1](https://user-images.githubusercontent.com/84587172/121970431-26f11e00-cd3c-11eb-8ea1-31a954b2ab81.png)

**2.5.4. Compare los valores de la tabla 2.1 y realice sus conclusiones.**

<div align="center">

|  **MALLA** | **Resultados Analíticos** | **Resulttados Simulados** |     
|    :---:   |           :---:           |         :---:             |
|     1      |           11.4 mA         |           11.5 mA         |
|     2      |           2.84 mA         |           2.85 mA         |
|     3      |           0.84 mA         |           488 uA          |

</div>
     
# 5 VIDEO 

# 6 CONCLUSIONES 

# 7 BIBLIOGRAFÍA
