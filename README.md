# ***Proyecto Diplomatura IA - Universidad de Palermo***
**Algoritmo de NLP + Clasificacion**


Partiendo de un dataset correspondiente a reviews de aerolíneas, se le aplica al campo de review escrita un algoritmo preentrenado de NLP para análisis de sentimiento. El mismo devuelve una nueva columna indicando si 
el mismo es 'positivo', 'negativo' o 'neutral' según corresponda. A partir de esta información, mas los ratings para distintos items como asiento, entretenimiento, wifi, etc. se aplican diversos algoritmos de 
clasificación según si la persona recomienda o no la aerolínea. Se selecciona el de mejor performance, se realiza hypertuning de sus parámetros y por último se identifican los features más importantes para dicho 
modelo; de manera de poder recomendarle a las aerolíneas que items ponderar para aumentar su cantidad de ventas de tickets. 
