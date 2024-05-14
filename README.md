﻿# AlgoritmosReto1
Hola Buenos días profesor .
 
 
Esta es mi entrega correspondiente al primer reto de la implementación de algoritmos en Jupyter.
En el archivo .ZIP hay dos carpetas,

primeraEjecucion y segundaEjecucion; cada una de ellas corresponde a una ejecución de los algoritmos con diferentes parámetros; son la exportación desde GOOGLE COLAB a página web guardada localmente, encuentro que FIREFOX es mejor mostrandoel contenido exportado que otros navegadores que piden recursos que no se descargaron.




primeraejecucion.
	El archivo principal es primeraejecucion.html, y los algoritmos están ejecutados con los siguientes parámetros:
	
	1. Torres de Hanoi: 8 discos
	2. Sucesión_de_Fibonacci:  n=20  n-ésimo término 
	3. Problema del cambio de moneda: monto = 63,  denominaciones = [1, 5, 10, 25]  
	4. Problema de las N Reinas: 7 Reinas


segundaEjecucion
 
 	1. Torres de Hanoi: 4 discos
	2. Sucesión_de_Fibonacci:  n=30  n-ésimo término 
	3. Problema del cambio de moneda: monto = 62,  denominaciones = [1, 5, 10, 20, 50] 
	4. Problema de las N Reinas: 10 Reinas
	
	

COMENTARIOS ACERCA DE LOS ALGORITMOS:

	1. Torres de Hanoi: Resuelto por técnica divide y venceras, se encuentra que con un conjunto de instrucciones reducido se puede resolver el problema que a simple vista es más complejo. En mi implementación hay dos formas de mostrar en pantalla; al principio lo hice como script de pithon en consola, así que se imprimien caracteres que representan los discos de cada torre, Al implementarlo para Jupyter, decidí incluir gráficas que igualmente muestran los movimientos de cada disco entre torres, pero de una manera más agradable a la vista.
	
	2. Sucesión_de_Fibonacci:  Se implementan dos funciones de fibonacci, de manera recrsiva y dinámica, se usa funciones par medir en tiempo en que demora cada implementación en llegar al n-ésimo termino, usando 20 y 30; La manera recursiba es pero por mucho la que más demanda recursos de tiempo, no me esperaba tanta diferenca a decir verdad.
	
	3. Problema del cambio de moneda: Resuelto por técnica de algotirmo voráz; hice varias pruebas y creo que tengo una respuesta a la pregúnta "CÓMO SE DETERMINAN LAS DENOMINACIONES", pienso que determinar el valor de una nueva moneda, pasa por ver si ese nuevo valor puede representarse con menos monedas ante un monto dado. Es decir, hice la prueba para un monto de 63 con las denominaciones [1, 5, 10, 25] , luego hice la prueba con el mismo monto pero con una nueva denuminación de 27 [1, 5, 10, 25, 27] ; el resultado es que se requieren más monedas. 
	
	4. Problema de las N Reinas: Resuelto por técnica de Backtracing, me costó resolverlo pero al fin lo logré, utilizo la estructura sugerida por el profesor, que consta de una TUPLA que indica el número de fila ejemplo: 
	
	TUPLA [0,1,2] significa un tablero:
	|Q [] []|
	|[] Q []|
	|[] [] Q|
	
	Al final utilizo una gráfica modificada para que parezca un tablero de ajedrez donde ubico las renas según la tupla solución.
	
