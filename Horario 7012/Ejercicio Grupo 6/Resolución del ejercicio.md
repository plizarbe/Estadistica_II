DESARROLLO DEL PROBLEMA: 
En cuanto al Supuesto de que No hay Heterocedasticidad en los residuos:
Según lo que es posible apreciar en el gráfico, a partir de la prueba de Park, se observa que los residuos no poseen una tendencia o patrón definido, los datos se encuentran dispersos y la varianza es negativa, lo que la hace igual a cero. En ese sentido, podríamos afirmar que sí se estaría presentando homocedasticidad en los residuos. Entonces, se cumple el supuesto que requiere que se verifique la falta de heterocedasticidad en los residuos. 


En cuanto al Supuesto de que NO existe una Relación Espúrea:
•	Distancia de Cook: Su valor es de 0.003. Entonces, como es menor a 1, se puede afirmar que no habrán valores influyentes dentro de los residuos.
•	Valor de influencia centrado (VIF): Su valor es de 0.015. Entonces, como es menor a 0.2, se puede afirmar que no habrán valores influyentes dentro de los residuos. 
Con esta información, se comprueba que, efectivamente, los coeficientes son independientes.

Comparación de Modelos

•	Debido a que la Variable independiente de “Rompimiento” no tenía un efecto sobre la variable “Tolerancia”, se decidió generar un nuevo modelo que no incluyese dicha variable para así comprobar qué modelo predice mejor la 	Tolerancia hacia la violencia. El modelo original contaba con siete variables y el nuevo modelo cuenta con seis, por ello, se comparan los modelos utilizando el R cuadrado corregido o ajustado. 
•	El R cuadrado corregido de este modelo de seis variables es mayor a 0.25, lo cual indica que existe un buen ajuste del modelo. Así el 84% de la variabilidad de Tolerancia se debe a los cambios en al menos una de las variables independientes.
•	Se observa que R cuadrado corregido para ambos modelos es similar (con una diferencia decimal de 0.4, pues para el modelo de siete variables que incluía “Rompimiento” el R cuadrado corregido era 0.843) por lo que podríamos sostener que ambos modelos serían igual de buenos en la predicción de la Tolerancia. 
•	No obstante, se prefiere el modelo original por obtener una mayor variabilidad. 

