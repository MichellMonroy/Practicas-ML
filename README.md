# Resumen

Este trabajo forma parte del proyecto PAPIME titulado "Propuesta de mejora a la
enseñanza del aprendizaje automático aplicado a la Ciencia de Datos a gran escala",
con el número de proyecto **PE106021**. Se propone la elaboración de un manual de
prácticas para estudiantes del nivel licenciatura, que ayude a mejorar el conocimiento
del Machine Learning (ML) y su aplicación en la ciencia de datos a gran escala (Big
Data).

El proyecto estará basado en diseñar, construir e implementar una guía de prácticas 
dirigida a los estudiantes a partir de sexto semestre en adelante de la Licenciatura
en Tecnologías para la Información en Ciencias (LTICs) o de otras licenciaturas de la
ENES Morelia que cuenten con los conocimientos básicos del ML.

Para realizar dicho proyecto, se tomará en cuenta la opinión de alumnos y docentes
de las diferentes licenciaturas, dentro de la ENES Morelia, con respecto a cuáles temas
son los que consideran de mayor importancia y que se deben impartir dentro de las
materias que utilizan el aprendizaje automático dentro del plan de estudios de la
LTICS.

El objetivo de este proyecto es el de mejorar la formación académica de los estudiantes dentro de la LTICS, 
así como mejorar la calidad de la enseñanza de este tema por parte de los docentes.

# Abstract

This work is part of the PAPIME project called "Proposal to improve the teaching
of machine learning applied to large-scale Data Science", with **PE106021** project number. 
The development of a computing laboratory manual for undergraduate students
is proposed in order to improve the knowledge acquisition of Machine Learning (ML)
and its application onto a large scale Data Science (Big Data).

The project is focused on designing, building and implementing a manual of computer 
laboratory practices aimed at students from the sixth semester onwards of the
Bachelor of Information Technology in Sciences (LTICs) and/or other degrees from
ENES Morelia with basic knowledge of the ML.

To carry out this project, opinion of students and teachers of different degrees,
within the ENES Morelia, will be taken into account with respect to which topics
are the ones that they consider most important and that should be taught within
subjects based on ML of the LTICs curriculum.

The objective of this project is to improve the academic training of students,
within the LTICs, as well as to improve the quality of teaching of this knowledge area
by the academic staff.

# Estructura del proyecto

Este repositorio constiste de dos carpetas principales:
- Manual
- Prácticas
En la carpeta "Manual" se encuentra el Manual de Prácticas el cual contiene toda la información relacionada al marco teórico y la metodología utilizada en este proyecto.

En la carpeta "Prácticas" se encuentran todas las prácticas desarrolladas en este proyecto, cada pŕactica se encuentra en una carpeta en la que se encuentra lo siguiente:
- Jupyter notebook donde se desarrolla paso a paso la práctica.
- Archivo **.pdf** en el cual se describe la metodología y el código usado en el Jupyter notebook. En el caso de la práctica 6, este archivo no es necesario debido a que lo necesario está explicado en el Jupyter notebook.
- Archivo **.md** donde se describe cómo descargar los datos utilizados en la práctica.

# Prácticas
| N°  Práctica | Nombre                                                     | Dataset                                         | Criterio de  Evaluación     | Descripción                                                                                                                                                                     |
|--------------|------------------------------------------------------------|-------------------------------------------------|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1            | Clasicación usando árboles de decisión                     | Pasajeros del Titanic                           | Exactitud y/o Métrica Fbeta | Construir un árbol de decisión para clasificar si los pasajeros del Titanic sobreviven o no dadas características como el sexo, edad, estatus, etc.                             |
| 2            | Predicción del costo de casa-habitación (Regresión Lineal) | California Housing                              | RMSE y/o MAE                | Construir un modelo de predicción para el costo de las casa habitación en el este de California (década de 1990).                                                               |
| 3            | k-vecinos más cercanos                                     | Pozos profundos del lago de Cuitzeo             | Precisión                   | Usar un dataset de pozos para hacer un modelo de KNN que agrupe elementos conforme al volumen de extracción de pozos en Michoacán (supervisado).                                |
| 4            | Aprendizaje no supervisado (k-means)                       | Online Retail K-means & Hierarchical Clustering | No aplica                   | Diseñar un modelo de K-means para hacer clasificación las transacciones de los clientes de un banco y así poder identificar a los diferentes clientes que hay (no supervisado). |
| 5            | Instalación y uso de Dask                                  | 3 nodos virtuales con CPU y GPU c/u             | No aplica                   | Mostrar cómo se realiza la instalación de Dask y cómo se usa para la manipulación de grandes volúmenes de datos.                                                               |
| 6            | Instalación y uso de HDFS                                  | 3 nodos virtuales con CPU y GPU c/u             | No aplica                   | Enseñar paso por paso cómo se realiza la instalación de Hadoop y cuál es la utilidad de los comandos de este mismo.                                                             |
| 7            | Predicción del clima (Regresión Lineal)                    | RUOA de 2015 a 2021                             | RMSE y/o MAE                | Usar los datos climáticos obtenidos por la RUOA para hacer un modelo de regresión lineal capaz de predecir el clima de los siguientes días.                                     |
