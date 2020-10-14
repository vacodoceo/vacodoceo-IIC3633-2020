# Comentario "Multi-Armed Recommender System Bandit Ensembles"

[![hackmd-github-sync-badge](https://hackmd.io/GpbMI625Th2oUaDNJkCfPA/badge)](https://hackmd.io/GpbMI625Th2oUaDNJkCfPA)


El *paper* se sitúa en un contexto en el que combinar distintos sistemas recomendadores para lograr un mejor *performance* ya es algo usual, sin embargo, no se ha estudiado en profundidad como utilizar esto en un ambiente más realista. Debido a lo anterior, el estudio propone un método en el que el sistema recomendador va adaptándose o modificándose a medida en que ocurren interacciones con las recomendaciones. Al igual que con los estudios de la semana pasada, me parece muy interesante dejar un poco de lado las métricas convencionales para medir qué tan bueno es un sistema, y empezar a utilizar métricas o casos más realistas para poner a prueba un sistema recomendador.

El método propuesto en el *paper* se basa en los *Bandit Recommender System*, sistemas explicados en la sección 2.2. El funcionamiento de este sistema se resume en tener una recomendación por cada sistema recomendador individual, y decidirse por uno según los resultados anteriores.

Para el experimento se utiliza el famoso *dataset* de *MovieLens*. A diferencia de otros sistemas recomendadores, en este caso se utiliza solo una pequeña parte del *dataset* (5% en este caso) para entrenar al modelo. Creo que este número es bastante pequeño, sin embargo, entiendo que hay que dejar buena parte del *dataset* disponible para simular interacciones iterativas para cada usuario. Con respecto a los parámetros del *bandit ensemble*, extrañé ver cómo estos podían incidir en los resultados de la recomendación.

Con respecto a los resultados, me parece curioso ver como el *Dynamic ensemble* se comporta tan mal, peor que sistemas recomendadores típicos o "base" como el *User-based kNN*. Por otro lado, también me parece interesante que el ![](https://i.imgur.com/aC253Z2.png) se comporte mejor que el *Thompson*, siendo que según la el método en que escoge el sistema recomendador es mucho más simple (muy evidenciable gracias a la Figura 2).


