# Laboratorio-2

PRÁCTICA N°02 ANÁLISIS DE MALLAS

1.1. OBJETIVOS DE LA PRÁCTICA

OBJETIVO GENERAL:

Compruebe de forma experimental el análisis de mallas, mediante la simulación de un circuito mixto, para poder aplicar los conocimientos adquiridos en la clase.
OBJETIVOS GENERALES:

Determinar el número de mallas que existen en el circuito mixto.
Usando de forma correcta los conceptos obtenidos de la Ley de Ohm.
Ejemplo de la Ley de los voltajes de Kirchhoff para encontrar el voltaje que se registra por cada malla.

2. MARCO TEÓRICO

RAMA
Se define como la parte o elemento que se encuentra entre dos nudos. Cabe recalcar que por todos los componentes de una rama circula la misma corriente.

NODO
Se le conoce como el punto de unión de 3 o más ramas. Es importante mencionar que la suma de las corrientes entrantes a un nodo debe ser igual a la suma de todas las corrientes salientes. (Ley de las corrientes de Kirchhoff).

MALLA
Una malla es el camino que forman 2 o más ramas de un circuito. Además en una malla la suma de todas las tensiones, cada una con su signo correspondiente, es igual a 0 (Ley de los voltajes de Kirchhoff). Esto se da porque la suma de todas las subidas de tensión debe ser igual a la suma de todas las caídas de tensión.

GRÁFICO DE RECONOCIMIENTO DE RAMAS, NODOS Y MALLAS


![image](https://user-images.githubusercontent.com/105291794/172507640-0884b6c2-a669-4f54-bad3-7f7542a2cd89.png)

ANÁLISIS DE MALLAS

![image](https://user-images.githubusercontent.com/105291794/172507655-5ed590a5-9f0c-4dc2-add0-288c73ae3d26.png)


![image](https://user-images.githubusercontent.com/105291794/172507979-87e8eac2-99f8-4e90-bf56-b77f251819c4.png)

![image](https://user-images.githubusercontent.com/105291794/172507996-2ffab831-a7aa-4f43-86e7-2bac51244aaa.png)

3.EXPLICACIÓN DEL PROCEDIMIENTO

![image](https://user-images.githubusercontent.com/105291794/172508048-29f7967d-d4cf-42cd-bccc-f3013dd48ef3.png)

Analisis del Circuito

![image](https://user-images.githubusercontent.com/105291794/172508147-18f99b61-fc5a-4e20-8ef7-6a07ee69f448.png)

Circuito armado en el simulador Tinkercad.

![image](https://user-images.githubusercontent.com/105291794/172508341-a5ba1407-5119-4e57-b487-793833529950.png)


Esquema obtenido del circuito en Tinkercad.

![image](https://user-images.githubusercontent.com/105291794/172508462-d0ae69fb-3b85-418f-a929-9389d00d3d1b.png)


Medición de cada una de las corrientes de malla.

![image](https://user-images.githubusercontent.com/105291794/172508499-7b4d712c-d8ec-4feb-b6ab-850e768e0d04.png)


4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Circuito armado para el análisis de mallas.

![image](https://user-images.githubusercontent.com/105291794/172508582-76d66917-f55e-4806-9944-63c3da8b215b.png)

Resultados obtenidos.

![image](https://user-images.githubusercontent.com/105291794/172508616-7efe8c9c-58f9-42fe-9080-db67d9a9e047.png)

Explicación del método de análisis de mallas.
Se ha asignado a cada una de las mallas un circuito imaginario basado la direccion de la fuente de mayor voltaje, formando una trayectoria cerrada.

![image](https://user-images.githubusercontent.com/105291794/172508651-f6c43c15-323f-4aab-b27e-7d99185fb1f2.png)

Resolución de los cálculos.
En primer lugar es necesario tener a todas las resistencias en un mismo valor, por lo que todas seran convertidas de kΩ a Ω.

![image](https://user-images.githubusercontent.com/105291794/172508687-19216b31-0391-4202-a4d5-e7f5461a8285.png)

Ecuación por cada malla ya definida

Malla 1

![image](https://user-images.githubusercontent.com/105291794/172508728-716c3f29-7277-4d01-90fb-18e42e56daca.png)

Malla 2

![image](https://user-images.githubusercontent.com/105291794/172509266-556dd05a-e429-455c-89d3-09e174d1a34e.png)

Malla 3

![image](https://user-images.githubusercontent.com/105291794/172509299-d42d2df1-fe75-4319-b6e8-687847c08068.png)

Cálculo de error.

![image](https://user-images.githubusercontent.com/105291794/172509346-bdea80d5-3a81-44b9-afcd-006ecee04e6c.png)

Al realizar el cálculo del error se puede notar que hay cierto porcentaje y aunque no es mucho podria influenciar en el circuito.

6. CONCLUSIONES

Para realizar correctamente el cálculo de corrientes por el método de mallas es necesario asignar el sentido a las corrientes de forma que se pueda aplicar la ley de Kirchhoff de las tensiones en cada una de las mallas a tratar.

Los resultados obtenidos manualmente como en el simulador (TINKERCAD), varian en una mínima proporción debido a los factores utilizados en los calculos, debido a esto se diría que nunca daremos con una medida exacta ni precisa solo una aproximación.

7. BIBLIOGRAFÍA

Floyd, T. (2007). Principios de Circuitos Eléctricos octava edicion. México: Pearson Educación: http://media.espora.org/mgoblin_media/media_entries/1455/Principios_de_circuitos_electricos.pdf

Electronnica. (20 de Septiembre de 2012). Electronica completa. Obtenido de: https://electronicacompleta.com/leyes-de-kirchhoff/?sfw=pass1653059613




















