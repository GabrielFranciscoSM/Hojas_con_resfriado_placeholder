# Hojas con resfriado
Proyecto de la asignatura VC (Visión por Computador) del grado en Ingeniería Informática por la UGR.

## Autores:
- Gabriel 
- Germán
- Miguel Ángel
- Pablo García Bas

## Abstract:

Modelo de Segmentación y Reconocimiento de patrones en imágenes, concretamente lesiones foliares causadas por agentes patógenos (hongos, bacterias, ácaros, etc.) en diferentes especies de árboles, haciendo uso de redes neuronales. Las imagenes de entrada mostrarían hojas con eventuales daños. El esquema de la red sería el siguiente: En primer lugar se aplicaría una CNN a la imagen para detectar la especie de árbol analizando la hoja, a continuación un YOLO para detectar y marcar las zonas afectadas, y por último otra CNN actuando en los rectángulos que proporcione el YOLO para clasificar el patógeno (o indicar que sólo hay tejido sano).

## Bases de datos:

[New Plant Disease Database](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset/data)
[Plant Leaf Diseases Dataset](https://www.kaggle.com/datasets/nirmalsankalana/plant-diseases-training-dataset)

