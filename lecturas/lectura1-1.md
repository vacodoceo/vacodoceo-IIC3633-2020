# Comentario "Item-Based Collaborative Filtering Recommendation Algorithms"

[![hackmd-github-sync-badge](https://hackmd.io/H2i-muloTxmw2zkQm-bcHg/badge)](https://hackmd.io/H2i-muloTxmw2zkQm-bcHg)


En este *paper* se explica a grandes rasgos como funcionan los sistemas recomendadores basados en *Collaborative Filtering*, dentro de los cuales menciona el *User-Based*, el más común, y también propone, analiza y expone resultados del *Item-Based*. Se explica también que el proponer este nuevo sistema recomendado *Item-Based* nace de distintos problemas que tiene el *User-Based*.

Leer este *paper* me sirvió bastante para enterarme y comprender el funcionamiento y los problemas de los sistemas recomendadores basados en filtros colaborativos. Pienso que se exponen los términos y componentes de estos tipos de sistemas recomendadores de forma básica, lo cual es bastante cómodo para leer aún cuando no tenía conocimientos de esta área antes.

En un comienzo no me agradó el *approach* que se propone en el *paper*, sin embargo, tras seguir entendiendo su funcionamiento y el porqué del *approach* me di cuenta que puede ser muy útil en algunos casos. De todas formas, siento que esta condicionalidad no se expone en la lectura. Por ejemplo, en un caso en donde la cantidad de *items* sea exacerbadamente mayor a la cantidad de *users*, probablemente un enfoque *Item-Based* no sea lo más óptimo.

Por otro lado, también hay aseveraciones que, o bien no me parecen válidas, o no se detallan lo suficiente para validarlas. Un ejemplo de esto es cuando se menciona que *"the less time an algorithm spends searching for neighbors, ... the worse its quality"*. A mi parecer, esa afirmación no es cierta si la búsqueda de *neighbors* se realiza de forma óptima teniendo los vecinos ordenados de forma inteligente. No sé si lograr esto sea posible, pero si no lo es, creo que sería oportuno explicarlo para darle más validez o dar a entender mejor las suposiciones en las que se basa el *approach* presentado.

Con respecto a las pruebas experimentales, sin tener mucho conocimiento del área puedo decir que me parecieron adecuadas, sobretodo el hacer pruebas variando el *train/test ratio*. Esto último debido a que establecer tal *ratio* suele ser al "ojo" en casos experimentales con poco conocimiento como los que he llevado hasta ahora, por lo que ver pruebas de este tipo en estudios da a entender que no existe un *ratio* correcto para todos los casos. Además, da a entender que vale la pena definir un óptimo antes de seguir con las pruebas del modelo.