# Comentario "Content-Based Recommendation Systems"

[![hackmd-github-sync-badge](https://hackmd.io/FUVGFKVERiC1ZR9Ztgfr8g/badge)](https://hackmd.io/FUVGFKVERiC1ZR9Ztgfr8g)

El paper es del 2007 y habla sobre los sistemas recomendadores del tipo *Content-Based*. Encuentro valiosa la introducción que hace, explicando que cosas tienen en común todos los sistemas de recomendación de este tipo y ejemplos de este, sin embargo, extrañé una contextualización del estado del arte en ese entonces. 

Con respecto a lo comentado en la sección 10.1 sobre como representar los datos, me parece muy valioso el haber empezado haciendo la distinción entre datos estructurados, no estructurados y semi-estructurados. De la misma manera, es interesante saber como se lidiaba con los datos no estructurados hace más de 10 años, cuando el *Deep Learning* no estaba lo suficientemente desarrollado para utilizar modelos de capas para clasificar datos de este tipo.

Quedé esperando más con respecto a la sección sobre como obtener o "crear" un perfil de usuario. Si bien presentó la información requerida (sus preferencias y un historial de interacciones), luego solo presenta desafíos que podrían ser abordados de mejor manera. Un ejemplo de esto es el desafío de que los *customization system* pueden proveer o bien muchos o pocos *items*. Siento que ese problema podría ser resuelto pidiendo más información al usuario sobre su perfil, en caso de faltar *items*, o bien, jerarquizando las preferencias del usuario en caso de sobrar *items*.

Luego de presentar las formas de representar los *items* y perfiles de usuario, se abarcan distintos algoritmos para emparejar estos *items* con los perfiles de usuario. Me parece que cada algoritmo queda bien descrito, sin embargo, hubiera valorado tener ejemplos de cada uno con el fin de entenderlos mejor y no tener que buscar en fuentes externas. A su vez, si bien creo que la forma en que se explican permite determinar los *pro's* y *con's* de cada uno, no se hace fácil poder compararlos entre sí.

Por último, extrañé resultados de este tipo de sistemas recomendadores, en especial con información "difícil de digerir" como lo es el *free-text*. Si bien en la sección 10.10 se da un *insight* del rendimiento de estos tipos de clasificadores, no hay ningún dato duro ni especificaciones de las condiciones en qué se realizan tales afirmaciones. Quedo con la sensación de que, a pesar de que este tipo de sistemas recomendadores puede funcionar bien en *datasets* estructurados, lo mejor sería utilizarlo en complemento de otro tipo de sistema recomendador, como puede ser uno colaborativo.

<!--- 
Content-Based -> Recomienda en base a la descripción de un item y de las preferencias de un usuario. 

Cosas que comparten: 
* Un medio para describir el item
* Un medio para crear un perfil de usuarios que describa los items que le gustan
* Un medio para determinar los items con el perfil del usuario para determinar qué recomendar

El perfil es creado y se actualiza automaticamente según las acciones del usuario
--->
