#### Proyecto de mentoría
#### *Herramientas de Data Science para dosimetría en medicina nuclear*
### **Facilitador:** P. Pérez

Proyecto de mentoría para la materia de [Análisis y Visualización](https://github.com/DiploDatos/AnalisisyVisualizacion).

## Herramientas de Data Science para dosimetría en medicina nuclear
# Análisis y Visualización

En imágenes médicas, la presentación de resultados de forma intuitiva es central para la comunicación con el médico. El físico médico debe ser capaz de presentar los resultados logrando proveer tanto información anatómica como metabólica en una misma imagen. En análisis y visualización se detectarán outliers, se definirán zonas de interés y se observarán características particulares de las imágenes.

En el presente proyecto realizaremos un trabajo de exploración sobre un conjunto de 2 imágenes de medicina nuclear a elección del/de la alumno/a. Cada imagen constituirá un dataset en sí mismo.

## Dataset

### Dataset 1

Encuentre una imagen 2D de medicina nuclear (puede ser de Cámara Gamma o un slice de una imagen de técnicas 3D). La imagen debe haber sido adquirida a distintos instantes de tiempo y debe ser anonimizada antes de su utilización. Se muestra a continuación, un ejemplo de serie de 3 instantes de tiempo en los que se adquirió la misma imagen.

<p align="center">
<img src="../pics/1-im1.jpg" alt="im1" height="200"/>
</p>

### Dataset 1

Encuentre una imagen 3D, también de medicina nuclear, tomada a distintos instantes de tiempo (4D).

### Consideraciones generales

Ambos datasets deben corresponder a imágenes de medicina nuclear, es decir, obtenidas a partir de la detección de fotones provenientes de emisión de radionucleidos previamente suministrados a un paciente. 

Ambos datasets deben encontrarse anonimizados y pertenecer, o bien a una base de datos pública para educación/investigación o a una clínica médica que las otorgue anonimizadas y con consentimiento escrito para estos fines (recomendable a los fines de poder contar con imágenes para el resto de las materias y poder discutir el dataset con quien las provéa, generalmente interesado/a en un estudio de estas características).

## Consignas

### Parte 1

Realice un análisis exploratorio sobre cada dataset. 

1. Encuentre en cada caso la distribución de los valores de cada pixel y su evolución en el tiempo.
2. Realizar análisis de estadística descriptiva sobre los datos, tanto en una como en múltiples variables. Moda, media, mediana y desviación estándar de un producto en particular.
3. Defina de alguna forma la información que pueda considerarse “ruido” y encuentre outliers.
4. ¿Existe alguna probabilidad condicional entre valores de pixels entre diferentes tiempos de adquisición? ¿Conviene tomar valores de píxeles directamente o es preferible agruparlos en grupos? Justifique.
5. Agrupe en un número que considere aceptable los datos de cada imagen y busque coeficientes de correlación entre grupos del mismo tiempo y grupos de distintos tiempos. Definido un conjunto de píxeles dentro de un grupo en la primera imagen, este grupo de píxeles debe pertenecer al mismo grupo en los tiempos siguientes.
6. Defina un criterio para poder dividir los datos en cada imagen en sub-regiones que pueda considerar “homogéneas”.
7. Grafique, en cada caso de los puntos anteriores, y realice la visualización que considere más óptima. Justifique la elección de la visualización.

### Parte 2

A partir de los resultados obtenindos en la Consigna 1, diagramar una comunicación visual interactiva de los resultados describiendo los aspectos principales del dataset elegido (outliers, ruidos, sub-regiones homogéneas, etc.).

La comunicación debe estar apuntada a un público técnico pero sin conocimiento del tema particular, como por ejemplo, sus compañeros de clase.

## Entrega

Utilice [Plotly](https://plot.ly/python/), [Bokeh](https://bokeh.pydata.org/en/latest/docs/gallery.html) o [Dash](https://dash.plot.ly/?_ga=2.107731778.1979278639.1554668584-1509392585.1554668584) (recomendable) para presentar los resultados.

**Deadline:** 15 días posteriores al finalizar la materia de Análisis y Visualización.
