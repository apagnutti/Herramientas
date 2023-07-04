# Herramientas-de-estadistica

### Introducción

En nuestro laboratorio desde hace más de treinta años estudiamos la asociación fijadora de nitrógeno (N2) que se establece entre Sinorhizobum meliloti y alfalfa, como sistema modelo de una interacción simbiótica bacteria-planta.

Teniendo en cuenta que la información extracromosomal representa la principal fuente de germoplasma adaptativo no ligado a funciones centrales del control celular (altamente plástica, móvil, y modelada por las necesidades funcionales que reclama el ambiente) y que muchas de las cepas de S. meliloti poseen una gran cantidad y variedad de plásmidos no simbióticos, llegando a representar altos porcentajes del tamaño total del genoma (aproximadamente 5%); nos propusimos abordar la caracterización funcional del moviloma plasmídico. Haciendo énfasis en el estudio de las relaciones entre el costo y los beneficios derivados de la presencia de los plásmidos crípticos.

Con el objetivo de analizar cómo dicho conjunto génico móvil impacta en la vida libre y simbiótica de los rizobios, movilizamos doce plásmidos crípticos distintos provenientes de una colección local al mismo contexto cromogenómico. Sobre este conjunto de cepas isogénicas portadoras de diferentes plásmidos, evaluamos los cambios en el fitness  en vida libre provocados por cada uno de ellos mediante ensayos competitivos de fitness.

### Ensayos competitivos de fitness

En estos ensayos evaluamos la competencia en vida libre entre la cepa S. meliloti 20MP6 libre de plásmidos accesorios y otra cepa S. meliloti 20MP6 con uno de los plásmidos crípticos.

![20mp6_20mp6+plas](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/57e39b67-906f-4a72-8bd1-d7b27635073d)

Durante los mismos evaluamos el crecimiento diferencial entre las cepas, mediante la comparación del número inicial y final de ambas cepas.
Para averiguar el número de cada una realizamos recuentos en gotas, valiéndonos de que la cepa 20MP6 es resistente a estreptomicina (Sm400) y las cepas con plásmidos son resistentes a estreptomicina (Sm400) y neomicina (Nm100).
De esta manera, en las placas con Nm100 obtenemos la concentración de la cepa con plásmidos, mientras que en las placas con Sm400 el número total de bacterias.
La concentración de la cepa S. meliloti 20MP6 sin plásmido se obtiene mediante la diferencia entre ambos recuentos.
Para cada condición, se realiza una placa de cada uno de los dos antibióticos.
Dentro de cada placa, que se siembran 10 gotas (réplicas técnicas) de cuatro diluciones diferentes, de manera de obtener un número de colonias adecuado para su recuento.

La condición inicial es un cultivo líquido con una mezcla de aproximadamente 1:1 de ambas bacterias. Realizamos recuentos en gota para obtener el número inicial exacto.
A continuación, el cultivo inicial se divide en cuatro cultivos para que crezcan de forma independiente por 16 horas (réplicas biológicas). Realizamos los recuentos correspondientes para averiguar las concentraciones finales de cada uno de los cultivos.
Finalmente se evalúa si existió un crecimiento diferencial entre las cepas debido a la presencia del plásmido.

![diseño_ensayo](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/f038850c-9905-4597-b1ab-8238e82fac54)

### Análisis de los resultados

El resultado del ensayo es una tabla que contiene los recuentos de las gotas para cada una de las condiciones correspondientes.

Al agrupar los recuentos según su "Momento" (inicial o final), "ATB o Bacteria" (Sm400/bact totales o Nm100/bact con plásmido),
"Réplica biológica" (0 para el momento inicial o 1,2,3ó4 para el momento final) y "Dilución o Factor" (4 valores para el momento inicial y otros 4 valores para el momento final),
se obtienen 40 grupos (8 grupos iniciales = 2 ATB * 4 DIL + 32 grupos finales = 2 ATB * 4 DIL * 4 Réplicas)

El recuento por gota se multiplica por el factor correspondiente a la dilución realizada para obtener la variable concentración "FR" (Factor*Recuento) que será a variable de interés.
Se trata de una variable de tipo cotinua.

### Análisis gráfico las distribuciones de frecuencias de la variable

El siguiente gráfico muestra la frecuencia de los valores de concentración FR para los dos ATB y en los momentos inicial y final.

![Histograma_FR_según_ATB_Momento](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/d84628d1-7a21-40ca-84e3-45a4bde8d00b)


El siguiente histograma muestra la frecuencia de los valores FR para los dos ATB únicamente en el momento inicial:

![Histograma_FR_según_Bacteria_Momento_ATB_Replica](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/cf20171f-b86e-425b-8d7e-a9798201a457)


Cada uno de los gráficos a continuación muestran las FR para ambos ATB, en el momento final, para cada una de las réplicas biológicas.

![Histograma_FR_según_Bacteria_Momento_ATB_Replica1](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/34861c81-046e-4579-b7cc-9367f383a607)

![Histograma_FR_según_Bacteria_Momento_ATB_Replica2](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/581683fa-354f-4b24-9eed-9e2a5621e1cd)

![Histograma_FR_según_Bacteria_Momento_ATB_Replica3](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/ba677f19-8447-48de-b08b-1279743c28ce)

![Histograma_FR_según_Bacteria_Momento_ATB_Replica4](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/8c53b34f-66d4-4894-9ea8-c54fdbe4c423)




### Medidas características de cada distribución (centralización y dispersión)

Las distribuciones de todos los grupos con datos se describen mediante los parámetros incluidos en la siguiente tabla.

Parámetros de centralización: media y mediana.
Parámetros de dispersión: desviación estándar, varianza y rango de valores.
Parámetro de asimetría: skewness

![image](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/b475f2a8-e47b-4104-acb7-89780ad2ec91)


### Estimación de los intervalos de confianza

En la siguiente tabla se muestran los límites de los intervalos de confianza para el 95% de seguridad.

![image](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/cbad3cdb-6bd0-41e0-add7-1d69656996a2)

### Determinación del tamaño de la muestra

Al evaluar el número necesario de réplicas técnicas encuentro que: 

El tamaño muestral/cantidad de gotas necesaria por grupo es: 4

### Ensayos de hipótesis

Compararé las medias de la variable FR para las poblaciones de ambas bacterias. 

Para saber qué test utilizar, primero debo saber si los datos se distribuyen normalmente y si las varianzas son similares entre las poblaciones.

1) En primer lugar evalúo si la distribución es normal dentro de cada uno de los grupos mencionados anteriormente. Para ello planteo las hipótesis y realizo el test de normalidad.

La hipótesis nula es que los datos tienen una distribución normal. La hipótesis alternativa es que los datos no se distribyen normalmente.

Los resultados del Normaltest indican que el p-value obtenido para 34 de los 35 casos es mayor a 0.05 por lo que la hipótesis nula no puede rechazarse y los datos tienen una distribución normal.

Para los análisis a continuación descarto el grupo que no se distribuye normalmente, porque además el número de colonias por gota era muy bajo.

![image](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/069d8bc4-38a6-4aa1-9093-7e8b7d015522)

2) En segundo lugar evalúo la similitud entre las varianzas de las poblaciones de las dos bacterias en cada una las réplicas biológicas realizadas.

La hipótesis nula es que no hay diferencia entre las varianzas. La hipótesis alternativa es que son significativamente distintas.

Los resultados del test Levene, que compara las varianzas de a pares (las dos cepas), indican que hay diferencias significativas entre las varianzas.
Ya que en todos los casos el p-value es menor a 0.05 y rechazo la hipótesis nula.





3) Por último, como las poblaciones tienen distribuciones normales y varianzas distintas, realizo una prueba de Welch para comparar las medias.
Al comparar los "FR" para cada ATB, la prueba de Welch arroja p-values menores a 0.05. Resultado que se repite y magnifica al comparar los "FR" para cada bacteria:

Media 20MP6 = media Sm o total - media Nm o plásmido

Desviación 20MP6 = desviación Sm o total + desviación Nm o plásmido

Por lo que puedo rechazar la hipótesis nula y las poblaciones tendrían la medias distintas.

Biológicamente esto indica que la presencia del plásmido tiene un impacto en el crecimiento de las bacterias en vida libre.

![image](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/90193e70-2d5e-4693-84cd-f544e2b77bf0)


### Interpretación del coeficiente de correlación y evaluación del ajuste de una recta de regresión

Utilizo el coeficiente de correlación de Pearson porque mis variables son continuas con distribución normal.

En las cuatro réplicas biológicas encuentro que no existe correlación entre la cantidad final de las bacterias de las cepas. Esto lo observo como un coeficiente cercano a 0 y un pvalue alto.

![image](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/41596f70-a612-4361-986f-db115697480f)

![Regresion_lineal_Replica_1](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/d36f4fd4-6de5-4d5e-9e78-665300fbca53)

![Regresion_lineal_Replica_2](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/591835c9-ccca-4085-b66c-b5e987034bd5)

![Regresion_lineal_Replica_3](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/f830acd0-2f84-438e-a713-4de4d3b5a969)

![Regresion_lineal_Replica_4](https://github.com/apagnutti/Herramientas-de-estadistica/assets/130510520/c247e950-3566-4a8f-9dc2-4635aa8b9c76)


Si bien ya lo sabía por la correlación de Pearson, en los gráficos también se observa que no existe correlación.


