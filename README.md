*Abstract*

Para este proyecto del curso Data Science II: Machine Learning para la Ciencia de Datos, se hace uso de un set de datos obtenido de una competencia de Kaggle en la cual se espera generar un modelo predictivo usando datos recopilados de las pruebas saber pro (examen realizado a los estudiantes de educación superior en Colombia para medir el nivel educativo). Mediante el uso de un set de datos de entrenamiento en el cual se cuenta con una columna que permite conocer el desempeño del estudiante, mediante una clasificación de 4 clases (baja, media baja, media alta y alta), se espera generar un modelo que al ser testeado con un dataset sin esta columna, permita una predicción lo más acertada posible del resultado del estudiante basándose en los factores presentes en las demás columnas (estrato socioeconómico, situación familiar, nivel educativo padres, situación laboral del estudiante, etc). En este primera entrega se hace un análisis preliminar del set de datos de erntrenamiento, con el fin de entender las columnas y su importancia dentro del data set, así como plantear hipotesis iniciales y verificar su pertinencia.


*Pregunta e Hipotesis*

*¿Que factores socio-económicos están afectando el resultado en las pruebas de estado de los estudiantes colombianos de educación superior?*

El objetivo final de este análisis es determinar esos factores y su importancia a la hora de determinar el resultado esperado para un estudiante de educación superior. Para ello primero se debe hacer un sondeo de los datos, una limpieza de los mismos y entender también algunas relaciones entre las variables socio-económicas que presenta la fuente de datos.

Inicialmente es posible teorizar el gran peso que seguramente tiene el estrato socio-ecomnomico y la situación laboral del estudiante (asumiendo que una mayor cantidad de recursos económicos y temporales podrían contrubuir a mejores resultados en las pruebas), sin embargo resulta interesante conocer también que relación puede tener la ubicación geografica, pues regiones más alejadas de las urbes principales suelen ser asociadas con un desempeño más bajo, así cómo sería valioso probar a que punto el nivel educativo de los padres puede tener una relación directa con el desmpeño de los hijos.

Algunas hipotesisi adicionales son el hecho de que no hay una diferencia significativa entre los resultados de diferentes programas (pues las pruebas suelen ser de conocimientos básicos y tener una prueba de especialidad para cada programa) y que sea posible ver que los resultados esten afectados por la tenencia o no de internet de una familia.
