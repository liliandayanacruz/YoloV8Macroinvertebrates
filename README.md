# YoloV8Macroinvertebrates
The aim of this repository is to collect the data and results of the "Clasificación Automática de Macroinvertebrados Como Bioindicadores de Calidad de Agua, Asistida por Inteligencia Artificial, Mediante Detectores de Piezas Semánticas" project (code INTD2-72) at Mariana University (Colombia).

The experimentation has two stages:
1. Initial experimentation according to the available baseline: https://github.com/liliandayanacruz/YoloMacroinvertebrates. The initial stage of the experiment aims to evaluate the previous configuration in the new dataset using YOLO version 03.
2. Advanced experimentation on the dataset with new classes and features for morphotaxonomic part detection.

## Classes (dataset) for labelling and experimentation

The classification will be done at family level. Since the categorisation in the FinBenthic database does not extend to family level, it was necessary to merge two or three categories. However, for this project, we decided to strike a balance in the number of images. Each category's dataset may contain between 800 and 900 images. The families are as follows:

1. Baetidae (order Ephemeroptera, class Insecta). The species available in the database are: Baetis niger (455 images) and Baetis rhodani (468 images). There are a total of 923 images. The labelled parts are: head, antennae, thorax, legs, abdomen, gills and fins.
2. Nemouridae (order Plecoptera, class Insecta): The available species in the database are: Nemoura (414 images) and Protonemura (387 images). The total number of images is 831. The labelled parts are: head, antennae, thorax, legs, abdomen, gills and fins.


