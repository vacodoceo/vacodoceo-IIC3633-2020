# Comentario "Document Clustering Based On Non-negative Matrix Factorization"

[![hackmd-github-sync-badge](https://hackmd.io/HcZ-zzoZT8m_UmRC6nfcQQ/badge)](https://hackmd.io/HcZ-zzoZT8m_UmRC6nfcQQ)


El paper, del 2003, propone una forma de *clusterizar* documentos que sobrepasa a los de ese tiempo (*latent semantic* y *spectral*) en cuanto facilidad y precisión. En el método propuesto se representa un documento en base a un vector en donde cada axis representa un tópico. En lo personal, es bastante interesante leer sobre cómo se trataban temas como clusterizar datos para mejorar el rendimiento de motores de búsqueda muchos años atrás, cuando uno no tenía más de 10 años.

La sección 2 me parece muy valiosa, ya que contextualiza sobre el estado del arte en ese entonces y pone al día con métodos o conceptos que uno no puede traer interiorizados aún. A su vez, da un breve *insight* de los distintos métodos de particionamiento de datos, explicando sus contras.

Con respecto a la explicación del modelo y como funciona, creo que es relativamente simple de entender, más aún con el "paso a paso" que da. Tener una comparación directa con SVD ayuda más aún a comprender cómo funciona y cómo se visualizan los *pro's* de NMF fente a SVD. Es interesante ver como hoy en día estructurar los datos como lo hacía NMF (1 axis por tópico y darle un peso a cada uno) parece lo más intuitivo y sensato, sin embargo, en ese entonces una representación como SVD era lo que "la llevaba".

Con respecto a la prueba práctica, creo que el *dataset* tiene sus falencias pero supongo que en el 2003 conseguir un *dataset* de calidad no es tan fácil como lo es hoy. Me extraña que mencionen una irregularidad tan notoria del *dataset* como lo es tener *clusters* 100 veces más grandes que otros sin nombrar o indagar sobre la implicancia de esto. 
