# Proyecto 2 – Análisis Inicial y Selección de Problema

## Descripción

El presente proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre distintos conjuntos de datos provenientes de diferentes dominios, con el propósito de comprender sus características, evaluar la calidad de la información disponible e identificar posibles problemáticas susceptibles de ser abordadas mediante técnicas de ciencia de datos y aprendizaje automático. La correcta selección del problema constituye una etapa fundamental para el desarrollo posterior de modelos predictivos y la generación de conocimiento útil para la toma de decisiones.

## Conjuntos de Datos Analizados

### 1. Salud Mental en Jóvenes

Fuente: Kaggle.

Este conjunto de datos contiene información relacionada con variables demográficas, hábitos de vida, condiciones académicas y factores asociados a la salud mental de jóvenes, permitiendo estudiar posibles factores de riesgo y patrones relacionados con alteraciones en el bienestar psicológico.

### 2. Rendimiento Académico de Estudiantes

Fuente: Kaggle.

El dataset reúne antecedentes académicos, familiares y sociales de estudiantes, incluyendo hábitos de estudio, ausencias y desempeño académico, facilitando el análisis de variables relacionadas con el rendimiento y el bienestar estudiantil.

### 3. Riesgo Materno en Gestantes

Fuente: Kaggle.

Este conjunto de datos contiene información clínica y demográfica de mujeres embarazadas, permitiendo evaluar factores asociados al riesgo materno durante la gestación y apoyar la identificación temprana de casos de mayor complejidad.

### 4. Fetal Health

Fuente: Kaggle.

El dataset contiene registros cardiotocográficos utilizados para evaluar el estado de salud fetal. Su objetivo es clasificar los casos en categorías normales, sospechosas o patológicas a partir de variables biomédicas.

## Resumen del EDA Inicial

### Salud Mental en Jóvenes

Se identificaron variables numéricas y categóricas relevantes para el análisis. Se detectó la presencia de valores faltantes, distribuciones heterogéneas y posibles relaciones entre factores personales y la variable objetivo, sugiriendo la necesidad de aplicar técnicas de preprocesamiento antes del modelado.

### Rendimiento Académico de Estudiantes

Se observaron variables académicas y familiares potencialmente asociadas con el desempeño estudiantil. Asimismo, se identificaron algunos valores faltantes que requerirán tratamiento previo al análisis predictivo.

### Riesgo Materno en Gestantes

El conjunto presenta variables clínicas relevantes para la evaluación del riesgo durante el embarazo. Se identificaron diferencias entre grupos que podrían ser aprovechadas mediante modelos predictivos orientados a la clasificación del riesgo.

### Fetal Health

El dataset incluye variables biomédicas derivadas del monitoreo fetal. Se observaron algunas categorías con menor representación, aspecto que deberá considerarse durante etapas posteriores de modelado para evitar sesgos en la clasificación.

## Problema Seleccionado

### Descripción del problema

El problema seleccionado consiste en predecir el riesgo asociado a alteraciones en la salud mental de jóvenes utilizando información demográfica, hábitos de vida, condiciones académicas y factores psicosociales. El objetivo es desarrollar un modelo de clasificación capaz de identificar tempranamente a individuos con mayor probabilidad de presentar dificultades relacionadas con su salud mental.

### Tipo de problema

Clasificación supervisada.

### Justificación

Se seleccionó este conjunto de datos debido a la creciente relevancia que ha adquirido la salud mental en la población juvenil y a la riqueza de variables disponibles para su análisis. Durante el EDA se identificó una variable objetivo claramente definida, junto con múltiples variables explicativas que podrían influir en el estado de salud mental de los individuos.

Además, el dataset presenta desafíos característicos de proyectos reales de ciencia de datos, incluyendo la presencia de valores faltantes, coexistencia de variables categóricas y numéricas, así como relaciones potencialmente complejas entre diversos factores personales, académicos y sociales. Estas características lo convierten en un caso adecuado para la aplicación de técnicas de aprendizaje automático orientadas a problemas de clasificación.

### Objetivos específicos

* Explorar las variables asociadas al estado de salud mental de los jóvenes.
* Identificar factores demográficos, académicos y de estilo de vida relacionados con la variable objetivo.
* Aplicar técnicas de limpieza y preprocesamiento de datos.
* Construir y comparar modelos de clasificación para predecir el riesgo asociado a problemas de salud mental.
* Evaluar el desempeño de los modelos utilizando métricas apropiadas para problemas de clasificación.

## Instrucciones para Ejecutar

1. Clonar o descargar el repositorio desde GitHub.
2. Instalar las librerías necesarias: pandas, numpy, matplotlib y seaborn.
3. Abrir los notebooks de Jupyter incluidos en el proyecto.
4. Ejecutar las celdas en el orden establecido para reproducir los análisis exploratorios.
5. Revisar las visualizaciones, resultados y conclusiones obtenidas en cada notebook.

## Autores

* Karla Caroca Henríquez

## Licencia

Este proyecto fue desarrollado exclusivamente con fines académicos y educativos.

