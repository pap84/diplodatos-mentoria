#### Proyecto de mentoría

#### *Herramientas de Data Science para dosimetría en medicina nuclear*

### **Facilitador:** P. Pérez

Proyecto Final de Mentoría en aplicaciones de Ciencia de Datos

Herramientas de Data Science para dosimetría en medicina nuclear
----------------------------------------------------------------

Aplicaciones de la ciencia de datos en dosimetría en Medicina Nuclear
=====================================================================

La dosimetría en terapia dirigida por radionucleídos ha evolucionado
notablemente en los últimos años. El uso cada día más extendido en aplicaciones
terapéuticas de los radionucleídos, las partículas y las energías involucradas,
implican nuevos desafíos y esfuerzos en la realización de cálculos dosimétricos
específicos.

Con el foco puesto en la distribución espacial de dosis a tridimensional a nivel
de vóxel, se propone un análisis de clústering para este tipo de aplicaciones,
como una forma automática de identificar inhomogeneidades agrupando vóxeles en
volúmenes de interés de acuerdo a su funcionalidad.

Se propone utilizar distintas técnicas de clústering entonces, para identificar
zonas de inhomogeneidades, encontrar automáticamente subvolúmenes dentro de un
determinado volumen y producir mapas de actividad acumulada directamente a
partir del ajuste de centroides o por medio de un proceso de segundo paso a
partir de las imágenes clusterizadas como un mapa.

Se estudiará además la posibilidad de identificar regiones de ruido excesivo.

 

Consignas
---------

1.  Leer el artículo de [Devoli et
    al](https://ieeexplore.ieee.org/document/4774240).

2.  Identificar los procesos en los que se involucran las técnicas de clústering
    para el análisis.

3.  Proponer distintos algoritmos de clustering conocidos para realizar una
    experiencia similar.

4.  Descargar las [imágenes anonimizadas
    disponibles](https://drive.google.com/drive/folders/1na45yJhNVWYu_pkMAO5DvdKViD-U5WB9?usp=sharing),
    las cuales funcionarán como dataset para el trabajo.

    1.  Las imágenes contienen:  
        a. 2 set de imágenes sobre región pelviana (t=0m y t=20m)  
        b. 1 imagen de un barrido de cuerpo completo (t=20m)

    2.  Los estudios son con Fluorocolina (Radioisótopo F-18) habiéndo inyectado
        0,075 mCi/kg

5.  Definir una estrategia para implementar el método propuesto por el artículo
    en su sección II.A con diferentes tipos de algoritmos.

6.  Cuántos clústers definiría a priori para estas imágenes? Justifique.

7.  Utilizando los algoritmos propuestos, encontrar subregiones y visualizarlas
    como se indica en la Fig. 1.

8.  En función del artículo leído y las imágenes recibidas, qué análisis de
    pros/cons puede hacer? Qué estrategias abordaría en caso de contar con
    imágenes a mayores tiempos? Qué mejoras propondría para la definición de
    subregiones?

9.  Presente los resultados utilizando un sistema de visualización que considere
    óptimo. Justifique.

 

**Deadline:** 15 días posteriores al finalizar la materia de Análisis y
Visualización.
