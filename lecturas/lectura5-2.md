# Comentario "Combining Predictions for Accurate Recommender Systems" 

[![hackmd-github-sync-badge](https://hackmd.io/2aOkMyddR4mNcf4VVzCjbg/badge)](https://hackmd.io/2aOkMyddR4mNcf4VVzCjbg)


El paper, publicado en el 2010, analiza predicciones realizadas mediante una combinación (*blending* de ahora en adelante) de algoritmos de recomendación del estado del arte (algunos de ellos vistos ya en clases). El estudio se realizó en un contexto en donde la "técnica" del *blending* ya era conocida y practicada, sin embargo, hasta el momento solo se hacía uso del *blending* por promedio o por combinación lineal. Es por lo anterior que la investigación toma rumbo en métodos más elaborados de *blending* en búsqueda de mejores resultados.

Primero que todo, con respecto al *approach* de hacer un *blending* más sofisticado me parece grandioso. Luego de estudiar distintos algoritmos de recomendación durante el semestre, notamos que cada uno tiene fortalezas, debilidades y casos de uso distintos. Esto da la intuición de que combinandoles de alguna forma, mejores resultados pueden llegar a ser posible. Esto también se puede ver como una analogía de como funcionan los equipos de personas, en donde cada persona tiene distintas habilidades/debilidades y probablemente algunos por sí solos funcionen mejor que otros, pero trabajando en conjunto es cuando se puede obtener mayor valor (*accuracy* en este caso).

Con respecto a la sección 2, encuentro muy valioso tener un resumen de algoritmos ya estudiados pero importantes para la lectura. Si bien fueron vistos hace poco, nunca está de más tener acceso a un resumen para refrescar la memoria. Por otro lado, leer sobre otros algoritmos sin entrar mucho en detalle nunca está de más.

Con respecto a la sección 3, un montón de álgebra y algoritmos complejos dificultaron el poder seguirle el hilo a cada técnica de *blending*, sin embargo, siento que se puede entender facilmente la "esencia" de cada una. Aún así, creo que todas son bastante complejas y dan para estudiarlas con tiempo por separado, cosa que creo que se escapa un poco del curso. 

Por último, me parece correcto el *dataset* utilizado y la forma en que se manejó. No tengo mucha experiencia en como manejar *datasets* para comparar distintos *approaches*, y ver la técnica de utilizar el *probe set* tanto para entrenar los experimentos de *blending* como para testearlos me parece novedoso e interesante. Sí creo que hubiera sido valioso hacer notar en base a qué tomaron la decisión de las proporciones de división, ya que se entiende como que hubiera sido arbitrario.
